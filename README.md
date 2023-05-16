# gh extension org-teams

To install the extension, run:

```bash
gh extension install yermulnik/gh-org-teams
```

## Usage

```
 gh org-teams --help
Usage:
  gh org-teams [-o|--ORG <ORG>] [-n|--NAME] [-u|--URL]

By default the ORG is obtained using the command \"gh org list --limit 1\".
```

## Examples

```bash
  ✗ gh org-teams
```

```
✗ gh org-teams -nu
[
  {
    "name": "ale_hernandez_liberon-alu0101225562",
    "url": "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/ale_hernandez_liberon-alu0101225562"
  },
  {
    "name": "casiano-rodriguez-leon-alumnoudv4",
    "url": "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/casiano-rodriguez-leon-alumnoudv4"
  },
  {
    "name": "casiano-rodriguez-leon-crguezl",
    "url": "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/casiano-rodriguez-leon-crguezl"
  },
  {
    "name": "claudio_nestor-yanes-mesa-alu0101229942",
    "url": "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/claudio_nestor-yanes-mesa-alu0101229942"
  },
  {
    "name": "jordi-bas-balcells-alu100965315",
    "url": "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/jordi-bas-balcells-alu100965315"
  },
  {
    "name": "parallel-computing-group-parallel",
    "url": "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/parallel-computing-group-parallel"
  },
  {
    "name": "santiago-villar-vazquez-alu0100990522",
    "url": "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/santiago-villar-vazquez-alu0100990522"
  }
]
✗ gh org-teams -u
[
  "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/ale_hernandez_liberon-alu0101225562",
  "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/casiano-rodriguez-leon-alumnoudv4",
  "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/casiano-rodriguez-leon-crguezl",
  "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/claudio_nestor-yanes-mesa-alu0101229942",
  "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/jordi-bas-balcells-alu100965315",
  "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/parallel-computing-group-parallel",
  "https://github.com/orgs/ULL-MII-SYTWS-2223/teams/santiago-villar-vazquez-alu0100990522"
]
✗ gh org-teams -n
[
  "ale_hernandez_liberon-alu0101225562",
  "casiano-rodriguez-leon-alumnoudv4",
  "casiano-rodriguez-leon-crguezl",
  "claudio_nestor-yanes-mesa-alu0101229942",
  "jordi-bas-balcells-alu100965315",
  "parallel-computing-group-parallel",
  "santiago-villar-vazquez-alu0100990522"
]
```
