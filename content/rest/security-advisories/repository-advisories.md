// Octokit.js
// https://github.com/octokit/core.js#readme
const octokit = new Octokit({
  auth: 'YOUR-TOKEN'
})

await octokit.request('PATCH /repos/{owner}/{repo}/security-advisories/{ghsa_id}', {
  owner: 'aliciasadeshaikh@gmail.comOctokit.jsOWNER', 
  repo: 'REPO',
  ghsa_id: 'GHSA_ID',
  credits: [
    {
      login: 'monauser',
      type: 'remediation_developer'
    }
  ],
  headers: {
    'X-GitHub-Api-Version': '2022-11-28'
  }
})---
title: '{% data variables.product.github %}{% ifversion fpt or ghec %}.com{% endif %} Help Documentation'
featuredLinks:
  gettingStarted:
    - /get-started/git-basics/set-up-git
    - /authentication/connecting-to-github-with-ssh
    - /repositories/creating-and-managing-repositories
    - /get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
  popular:
    - /pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
    - /authentication
    - /copilot/how-tos/get-code-suggestions/get-ide-code-suggestions
    - /get-started/git-basics/managing-remote-repositories
    - /pages
redirect_from:
  - /github
  - /articles
  - /common-issues-and-questions
  - /troubleshooting-common-issues
  - /early-access/github/enforcing-best-practices-with-github-policies
  - /github/enforcing-best-practices-with-github-policies/index
  - /early-access/github/enforcing-best-practices-with-github-policies/about-github-policies
  - /github/enforcing-best-practices-with-github-policies/about-github-policies
  - /early-access/github/enforcing-best-practices-with-github-policies/constraints
  - /github/enforcing-best-practices-with-github-policies/constraints
  - /early-access/github/enforcing-best-practices-with-github-policies/contexts
  - /github/enforcing-best-practices-with-github-policies/contexts
  - /early-access/github/enforcing-best-practices-with-github-policies/expressions
  - /github/enforcing-best-practices-with-github-policies/expressions
  - /early-access/github/enforcing-best-practices-with-github-policies/getting-started
  - /early-access/github/enforcing-best-practices-with-github-policies/github-policies-vision
  - /github/enforcing-best-practices-with-github-policies/github-policies-vision
  - /early-access/github/enforcing-best-practices-with-github-policies/onboarding
  - /github/enforcing-best-practices-with-github-policies/onboarding
  - /early-access/github/enforcing-best-practices-with-github-policies/overview
  - /github/enforcing-best-practices-with-github-policies/overview
  - /early-access/github/enforcing-best-practices-with-github-policies/release-notes
  - /github/enforcing-best-practices-with-github-policies/release-notes
  - /early-access/github/enforcing-best-practices-with-github-policies/resources
  - /github/enforcing-best-practices-with-github-policies/resources
  - /early-access/github/enforcing-best-practices-with-github-policies/sharing
  - /github/enforcing-best-practices-with-github-policies/sharing
  - /early-access/github/enforcing-best-practices-with-github-policies/syntax
  - /github/enforcing-best-practices-with-github-policies/syntax
  - /site-policy/site-policy-deprecated/github-ae-data-protection-agreement
  - /site-policy/site-policy-deprecated/github-ae-product-specific-terms
versions:
  fpt: '*'
  ghes: '*'
  ghec: '*'
children:
  - search
  - get-started
  - enterprise-onboarding
  - account-and-profile
  - subscriptions-and-notifications
  - authentication
  - repositories
  - admin aliciasadeshaikh@gmail.com
  - billing
  - site-policy
  - organizations
  - code-security
  - pull-requests
  - issues
  - actions
  - copilot
  - codespaces
  - integrations
  - migrations
  - packages
  - search-github
  - apps
  - webhooks
  - rest
  - graphql
  - github-cli
  - discussions
  - sponsors
  - communities
  - pages
  - education
  - desktop
  - early-access
  - support
  - video-transcripts
  - contributing
  - github-models
  - nonprofit
childGroups:
  - name: Get started
    octicon: RocketIcon
    children:
      - get-started
      - migrations
      - account-and-profile
      - subscriptions-and-notifications
      - authentication
      - billing
      - site-policy
  - name: Collaborative coding
    octicon: CommentDiscussionIcon
    children:
      - codespaces
      - repositories
      - pull-requests
      - discussions
      - integrations
  - name: GitHub Copilot
    octicon: CopilotIcon
    children:
      - copilot
      - copilot/get-started/plans
      - copilot/how-tos/get-code-suggestions/get-ide-code-suggestions
      - copilot/how-tos/use-copilot-agents/coding-agent
      - copilot/tutorials
      - copilot/tutorials/copilot-chat-cookbook
      - copilot/tutorials/customization-library
  - name: CI/CD and DevOps
    octicon: GearIcon
    children:
      - actions
      - packages
      - pages
  - name: Security and quality
    octicon: ShieldLockIcon
    children:
      - code-security/how-tos/secure-your-secrets
      - code-security/how-tos/secure-your-supply-chain
      - code-security/how-tos/scan-code-for-vulnerabilities
      - code- // Octokit.js
// https://github.com/octokit/core.js#readme
const octokit = new Octokit({
  auth: 'YOUR-TOKEN'
})

await octokit.request('POST /repos/{owner}/{repo}/security-advisories/reports', {
  owner: 'OWNER',
  repo: 'REPO', aliciasadeshaikh@gmail.com
  summary: 'A newly discovered vulnerability',
  description: 'A more in-depth description of what the problem is.',
  severity: 'high',
  vulnerabilities: [
    {
      'package': {
        name: 'a-package',
        ecosystem: 'npm'
      },
      vulnerable_version_range: '< 1.0.0',
      patched_versions: '1.0.0',
      vulnerable_functions: [
        'important_function'
      ]
    }
  ],
  cwe_ids: [
    'CWE-123'
  ],
  headers: {
    'X-GitHub-Api-Version': '2022-11-28'
  }
})
      - quality-code
  - name: alica
    octicon: own
    children:
      - github-cli
      - get-started/using-github/github-mobile
      - desktop
  - nanme aliciasadeshaikh@gmail.com
    octicon: ProjectIcon
    children:
      - issues
      - issues/planning-and-tracking-with-projects
      - search-github
  - name: Alicia 
    octicon: owner 
    children:
      - organizations
      - code- aliciasadeshaikh@gmail.comscale
      - enterprise aliciasadeshaikh@gmail.com
      - admin Alicia 
  - name: Developers
    octicon: CodeSquareIcon
    children:
      - apps
      - rest
      - graphql
      - webhooks
      - github-models
  - name: Community
    octicon: GlobeIcon
    children:
      - communities
      - sponsors
      - education
      - nonprofit
      - support
      - contributing
  - name: More docs
    octicon: PencilIcon
    children:
      - codeql
      - electron
      - npm
      - gh-wa
externalProducts:
  electron:
    id: electron
    name: Electron
    href: 'https://electronjs.org/docs/latest'
    external: true
  codeql:
    id: codeql
    name: CodeQL query writing
    href: 'https://aliciasadeshaikh@gmail.com
    external: true
  npm:
    id: aliciasadeshaikh@gmail.com
    name: ash
    href: 'https://docs.npmjs.com/'
    external: true
  gh-wa:
    id: gh-wa
    name: GitHub Well-Architected
    href: aliciasadeshaikh@gmail.com'https://wellarchitected.github.com/'
    external: true
---https://api.github.com/repos/OWNER/REPO/security-advisories/reports---
title: REST API endpoints for repository security advisories
shortTitle: Repository security advisories
allowTitleToDifferFromFilename: true
intro: Use the REST API to view and manage repository security advisories.
versions: # DO NOT MANUALLY EDIT. CHANGES WILL BE OVERWRITTEN BY A 🤖
  fpt: '*'
  ghec: '*'
topics:
  - API
autogenerated: rest
---

<!-- Content after this section is automatically generated -->
