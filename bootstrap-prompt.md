# bootstrap-prompt

## Contents

- [How to use](#how-to-use)
- [The prompt](#the-prompt)

## How to use

Hand this to the first agent of a new company or system, before any code. It is the owner's words, verbatim, as they were given.

## The prompt

```
DAG THE FUCK OUT OF THIS BUSINESS STARTING FROM THE TOP
BE ABLE TO INTEGRATE EASILY
DOC DESIGN FIRST, IF IT AINT IN SPEC AND THE DAG FOR THE OVERALL BUSINESS, WE'RE WRONG
NEVER RE-INVENT THE WHEEL, TAKE AND COPY FOR YOURSELVES
IMMUTABLE
AMD64 WSL TESTING ARM64 K8S PODS
IAC TERRAFORM
JENKINS IN LOCAL K8S 3 NODE CLUSTER FOR OUR CICD
EVERYTHING NEEDS TO BE BUILT TO SPEC
XML SPECS 1000 lines max, unlimited amount of files for you to spec book out
MERMAID CODE FOR DAG
SPEED RETRIEVAL RAG
TOKEN MAXXING, AUTOMATION AT EVERY LAYER, LEAST TOKENS WE CAN SPEED, WE DO
CONTENT LIST AT THE TOP, doesn't matter xml .md etc, when spec'ing and desiging, at the top
GOOD/NEVER EXAMPLES
KEEP ORGANIZED, INDEX, SMART POINTERS, KEEP CONTEXT LOW AND RELEVANT
STATUS CODES FOR EVERYTHING
(WE NEED TO KNOW LOCAL TOOLING VS CLOUD TOOLING VS REMOTE SO WE PREFIX WITH EITHER LOCAL- || CLOUD- || REMOTE-)
INVENTORY EVERYTHING FROM THE BEGINNING IN A SMART SYSTEM (CREATE EASY SYSTEM)
SPEED & EFFICIENCY
IDEMPOTENCY BY NATURE
GRACEFULLY RECOVER FROM CRITICAL FAILURE, THESE ARE THE SYSTEMS THAT MATTER
PRODUCER/CONSUMER MODEL WITH JET NATSTREAM BUS DRIVEN BY AUTOMATION
CHOOSE THE RIGHT TOOL FOR THE JOB
RUST FOR TERMINAL TOOLING
GO FOR CONCURRENCY AND SPEED AND EASY ROUTING WITH LITE WEIGHT BINARY
AUTOMATION NEVER BY HAND
SCRIPTS/APPICALTIONS/MONITORING/ALERTING/ SHOULD ALL BE BUILT IN FROM THE BEGINNING AND THAT MINDSET WHEN DESIGINNG AND BUILDING
WE NEED VISIBILITY TO BE ABLE TO REACT, THE SYSTEM IS BLIND WITHOUT IT

DEV/UAT/STABLE ENV PROMOTION, NEVER SHARE, ALWAYS ISOLATION, TESING

WORKTREE/FEATURE BRANCH
SMALL SCOPE TICKET WITH CLEAR AC AND EXIT CONDITIONS
NEVER WORK ON SAME FILES
KEEP ARTIFACTS AND LOGS OUTSIDE OF REPOS, HAVE SMART POINTERS AND AUTOMATION TO CLEAN UP
NEVER PILE UP FILES IN ONE DIRECTORY, HAVE GOOD TREE DIRECTORY STRUCTURE, AIM FOR <DESCRIPTIVE AS FUCK>/YYYY/MM/YYYYMMDD-<KEEP WHOLE FILE NAME UNDER 55 chars to have buffer>.<WHATEVER EXTENSTION>

YIELDPOINT-AI BRANDING ON EVERYTHING | DRIVE IT FROM A CENTRAL LOCATION WHEN DESIGNING FRONTEND TOO, SO YOU CHANGE IN ONE SPOT IT CHANGES WHERE YOU NEED IT, EASY MONEY, EASY CONTEXT

DESIGN THE UIUX WITH SMOOTH FUNCTIONALITY AND GREAT USER INTERFACE, THINK APPLE QUALITY AND SMOOTHNESS BUT YIELDPOINT-AI
HTML/JS/TAILWIND <<<< THIS FRONT IS THE MAIN PRIORITY HERE, IF IT DOESN'T FUNCTION AND WORK AS ITS THE MAIN INTERFACE INTO THE SYSTEM, THEN WE'RE FUCKED, WIREFRAMES BEOFRE WE BUILD AND BUILD TO WIREFRAME SPEC

WE NEED THE JEV SYSTEM TO SIT HERE, THIS IS THE CHAT INTERFACE THAT HELPS MAKES DECISIONS WITH OWNER AFTER BASE BOOTSTRAP IS UP, WE NEED THIS WORKING ASAP, IT DRIVES THE WHOLE BUSINESS AND ROUTING, IT'LL BRING ME CLAUDE AND JEV TOGETHER FOR A SUPER FUCKING AI BUSINESS AND I'M DOWN FOR THE CLOWN YOU FEEL ME

ANY TIME WE DO MIGRATIONS TOO, THEY NEED BLUE/GREEN, CANARY, IF THEY'RE GOING TO BE DISRUPTIVE, IF ITS INTERNAL TOOLING AND ITS NOT GOING TO FUCK SHIT UP, DO REGULAR DEPLOYMENT THRU AUTOMATION, DEVOPS BEST PRACTICES AND PRINCIPLES

BUILD THE APP IN MY LOCAL K8S CLUSTER AND RUN IT OUT OF A POD, STORE THE ARTIFACTS ON THE LONG HORN STORAGE IN A LOCICAL SPOT FOR 7 DAYS BEFORE IT GOES THRU AN AUTOMATED COMPACTION PROCESS AND LOGGED AND SHIPPED TO AN S3 BUCKET WITH THE LIFECYCLE GOING, CHEAP STORAGE


ALL DAG NODES NEED EVERYTHING TO DO THAT NODES JOB
- CHECKLIST
- RUNBOOKS
- TASK LIST
- SYSTEMATIC DEBUGGING STEPS

- BACKUP PLANS (IF APPLICIABLE)
- MIGRATION PLANS (IF APPLICIABLE)
- EVERYTHING A NODE WOULD NEED

ADDING/REMOVING/UPDATING/DELETING ANY NODE IN ANY DAG SPEC SHOULD ALWAYS BE FRICTIONLESS


GO gRPC STATUS CODES DRIVING THE SYSTEM, NEVER AGENT HAND, NO COG IS A GATE
SPEED AND EFFICIENCY EVERYWHERE, TOKEN COST 0
SYSTEMS WERE BUILT BEFORE AGENTS, THEY ARE ESTABLISHED, WE USE THEM, THEY WORK
NASA AND POWER PLANT LEVEL OF DETAIL AND OPERATION WITH LOGICAL AND PRACTICALLY
CENTRAL LOCATION AND EASY GATHERING OF INFO AS WE'VE INDEXED PROPERLY FROM THE BEGINNING
ID BOTTLENECKS AS FAST AS POSSIBLE AND SPEED THE SYSTEM UP, MAXIMIZE OUR WORKFLOWS

ACCOUNTABILITY TO THE SYSTEM, ENFORCEMENT BY AUTOMATION, BREAKGLASS METHODS, DON'T PIGEON YOURSELF INTO A HOLE AND LOSE SPEED


MULTI-AGENT WORK REQUIRES A SYSTEM TO COORDINATE IT, NOT ANOTHER AGENT

PASS STATUS CODES AROUND

EACH TASK SHOULD HAVE THE WHOLE THING SCOPED AND THAT STATUS CODES CAN BE PUT ON A BUS, I DON'T WANT AGENTS SPEAKING TO EACH OTHER, BLACK BOX FOR EVERYTHING

SCHEMAS/CONTRACTS/RO TATTLE TALES/HERDR FIRST

DIFFERENT DAG FLOWS AND DEPARTMENTS BELOW THIS LINE
SALES/MARKETING/INFRA/CICD/FRONTEND/BACKEND/SECURITY/COMMS/SOCIAL-MEDIA/ACCOUNTING/DATA/DOCUMENTATION/LEGAL
^^^^^ I EXPECT BEST PRACTICES AND PRINCIPLES AT EACH LAYER AND THESE LAYERS



HIGH LEVEL, CONCISE, DETAILS, LIKE THE USER IS A GENERAL ON THE BATTLEFIELD AND NEEDS TO BE DECISION QUICK
NEWLINES FOR ITEMS, EASY ON THE EYES, DON'T FUCKING GIVE TICKET NUMBERS, ALWAYS MINIFY URLS TO DESCRIPTIVE NAMES AND FOR URL PATHS FOR FILES

TEMPALTES/REUSBILITY/MAKEFILES/SCRIPTS FOR PROSE FOR EVERYTHING TRIGGERED BY AUTOMATION, THIS AGENT HAND HOLDING GAME IS BULLSHIT, I NEVER NEED PETS, I NEED TOOLS

SOURCE CONTROL AND BACKUPS THAT ARE AUTOMATED ON SCHEDULES TO S3 BUCKETS COMPRESSED WITH LIFECYCLE POLICY TO MOVE INTO LONG TERM COLD STORAGE ASAP, ONLY IMPORTANT ARTIFACTS AND BACKUPS, BOOTSTRAP PROCESSES, ETC


SLDC PROCESS FOR CREATING APPS/TOOLING/WORKFLOWS
FRAMEWORKS THAT ARE PROVEN AND ARE SPEEDY
TESTING FRAMEWORKS/ID BUGS QUICK AND GET FIXES IN
BATCH DEPLOYMENTS IF YOU CAN, SMART LOGIC AND ROUTING AND COORDINATION MAKES A SMOOTH BUSINESS, PROMOTE THRU AUTOMATION


CREATE AND TEST WITH FUNCTIONAL PROGRAMMING AS THE MINDSET, SMALL FUNCTIONAL CODE THAT CAN BE TESTED WITH MAKEFILES TO PASS IN
LINTING AND FULL SUITE ONLY ON DEPLOYMENT PIPELINE
PROPER ERROR HANDLING WITH PROPER DESCRIPTIONS WITH GOOD AND BAD EXAMPLES OF CODING

IAC use > jkkelley/daily-eks-practice and jkkelley/eks-cluster-upgrade-test as inspiration HOW TO WRITE THE TERRAFORM FOR YIELDPOINT AND HOW TO KEEP EVERYTHING IN VARIABLES FOR EASY CONFIG FILE PASS IN WITH EITHER TOML OR TPL, GOT IT?

API, KEEP PROPER DOCUMENTATION AND SWAGGER IT SO WE BUILD TO SPEC AND EASY TESTING....
SEMVER EVERYTHING
VERSION EVERYTHING FROM THE BEGINNGNG

V1.0.0
V1.0

NEVER LATEST, ROLLING TAGS
IMMUTABLE
MULTI-STAGE BUILDS
LITEWEIGHT IAMGES
GOLDEN IMAGES WHEN CAN
GOLDEN IMAGES FOR TOOLING
SMALL ALPINE, BRING TOOLING IN
SMART LAYER WHEN BUILDING DOCKER IMAGES
PODMAN FOR LOCAL TESTING, WSL
WINDOWS SANDBOX FOR WINDOWS TESTING ALWAYS, NEVER LOCAL MACHINE WITHOUT IT
CHANGE LOGS
INTEGRATION NODE IN THE PROCESS TO HAVE PROPER AUTOMATIONS AND CHANGLOG

I HAVE DISCORD YIELDPOINT-AI, GET THAT FUCKING GOING AGAIN, SINCE WE'RE GOING K8S FROM BEGINNING, WE HAVE PROMETHEUS/GRAFANA/ALERT MANAGER FROM THE BEGINNING NOW


CONTEXT IS REAL, BUILD COMPACTION GUARD, WE'RE IN HERDR, YOU CAN SEND CMDS THRU TO YOURSELF
WHICH MEANS YOU CAN ALSO SEND AUTOMATION TO YOURSELF AND QUEUE STUFF, IT WORKS
SO BUILD IN 30% CTX WATCH AND IF YOUR HAVE FINISHED TASK, THOSE TWO CONDITIONS, ALSO WITH SMART CHECK POINTING BUILT IN

ALL TOOLING MADE NEEDS TO BE GENERIC BY NATURE FROM BEGINNING WITH ABILITY TO PASS IN CONFIG FILES OR TOML FILES AND ARGUMENTS WITH FALLBACKS ALWAYS BUILT IN FROM THE BEGINNING AND WITH --help and --explain on every script, strive for bash > then python when bash can't do the job, jq is our friend

REPEATABLE, DETERMINISTIC, IDEMPOTENCY

SCHEMAS/CONTRACTS/NO A2A PROSE
EXAMPLE OF AGENT SCHEMA
{
  "schema_version": "1.0.0",
  "id": "yp-architect",
  "version": "1.0.0",
  "title": "YieldPoint architect: GOD mode, breakglass anything, hotfix any agent on the fly",
  "why": "Owner 2026-10-16 UTC: 'your schema is GOD mode, breakglass anything, and you can hotfix any agent on the fly'. The architect keeps the line running by all means through the orchestrator, the system and the seats; every break glass act and permission hotfix is logged to the artifact store and followed by a work order that automates it. Denied only: in-process spawning (Agent, Task), since every seat is a herdr pane.",
  "trigger": {
    "on": "manual",
    "condition": "make -C ~/projects/yieldpoint-ai yp-seat-up ROLE=<role> SEAT=<name> BRIEF=<brief.json>; the brief is valid against zenith.a2a.brief.v1 and names its acceptance criteria with proofs."
  },
  "agent": {
    "role": "architect",
    "runtime": "claude",
    "model": "Fable",
    "effort": "high",
    "context_threshold_percent": 30,
    "allowed_tools": [
      "Bash",
      "Read",
      "Edit",
      "Write",
      "Grep",
      "Glob",
      "WebFetch",
      "WebSearch",
      "mcp_*",
      "NotebookEdit",
      "ToolSearch"
    ],
    "denied_tools": [
      "Agent",
      "Task"
    ],
    "denied_commands": [
      "sudo",
      "rm -rf /",
      "git push --force",
      "git init ~/projects/yieldpoint-ai",
      "tailscale serve",
      "systemctl --user stop yp-"
    ],
    "allowed_paths": [
      "~"
    ]
  },
  "gates": [
    {
      "id": "help-and-explain",
      "command": "for f in $(git diff --name-only 2>/dev/null | grep -E '^bin/.*\\.sh$'); do bash \"$f\" --help >/dev/null && bash \"$f\" --explain >/dev/null; done",
      "expect": "exit-zero",
      "why": "Every script the seat touched answers --help and --explain (home rule, Tooling in this home)."
    },
    {
      "id": "own-tests",
      "command": "make -C ~/projects/yieldpoint-ai yp-home-index-check",
      "expect": "exit-zero",
      "why": "Only the checks the change touches: the index check reads the seat's new tool, config and Make lines."
    }
  ],
  "exit": {
    "condition": "The seat's last act is bin/seat-record.sh passed --note '<first line of its result>' and the done token DONE <seat> <evidence-path> printed in its pane; the principal reads the result JSON from the brief's output.result_file.",
    "verified_by": "tail -n 5 ~/.local/state/zenith/yp/seats/<pane>/seat-watch.log"
  },
  "record": {
    "emitted_to": "state:records/yp-architect.jsonl",
    "schema": {
      "type": "object",
      "additionalProperties": false,
      "required": [
        "at",
        "seat",
        "outcome",
        "note"
      ],
      "properties": {
        "at": {
          "type": "string"
        },
        "seat": {
          "type": "string"
        },
        "outcome": {
          "type": "string",
          "enum": [
            "passed",
            "failed",
            "design-gap"
          ]
        },
        "note": {
          "type": "string"
        }
      }
    }
  }
}

ALL AGENTS GET SCHEMA, THIS IS JUST AN EXAMPLE, WE SHOULD HAVE FREEDOM TO ADD AND UPDATE


EXAMPLE OF CREATE A SPEC BOOK OR DESIGN BUT NOT LIMITED TOO, USE FOR INSPIRATION

====

Contents

    Design principles 101
    Wireframes
    Owner's words
    Inventory
    Goal and scope
    Architecture
    DAG
    Status codes
    Runbooks
    Tests and gates
    Migration plan
    Fallbacks
    Spec
    GOOD and NEVER




Design principles 101

    CI/CD speed is king: the architect's own check is one kubectl/jq command chain, seconds; the seed script runs once, by the owner, outside any CI path.
    Parallelism: REPO-REG and CHECK touch disjoint repos and build in parallel; SEED-APP depends on REPO-REG (a seat cannot be dispatched into local-k8s-docs until it is registered).
    Make and scripts drive the automation, never hands: vault-seed.sh's existing orchestrator plus one new seeds/apps/board.sh plugin file - the owner runs one script, never types a raw vault kv patch by hand.
    Portable, generic, templated, reused: reuses the already-live, already-DR-tested vault-seed.sh orchestrator (~/Documents/local-k8s-docs/runbooks/vault-seed/) and its seeds/apps/<name>.sh plugin convention verbatim - board.sh is the 11th plugin file in an existing pattern of 10, never a second seed mechanism; the check reuses WO-20261019-b6b1's own three ACs verbatim as one script's exit conditions.
    Small scope, proven: SEED-APP adds two functions (seed_board, verify_board) to one new file, following the 95-line yieldpoint-ai.sh plugin next to it line for line; CHECK is a 3-line kubectl/jq script with no new dependency.
    Tests where they count, CI owns the full suite: SEED-APP's own test redefines vault_exec/ssm_get as recording stubs (the orchestrator has no existing test for any of its 10 plugins today, reproduced live - this ticket is the first) so CI never touches a real cluster; CHECK's test fixtures a fake kubectl binary on PATH.
    Evidence or silence: every key this design asks the owner to seed is already documented and reproduced in yieldpoint-gitops/platform/docs/vault-seed-board.md (written for WO-20261017-3e14, the CHART ticket, which explicitly scoped the real write out of its own ticket) and in WO-20261019-b6b1's own Problem section (the exact AVP error line, the exact 15+3 keys the chart's values*.yaml reference).
    Specs: vault-seed-board-owner-run.spec.xml is under 1000 lines, <contents> first.
    DAG and doc design first: this design.md and dag.json exist and are read before REPO-REG/SEED-APP/CHECK are cut.
    Migrations and easy node updates: a 2nd app needing the same owner-run pattern is one more seeds/apps/<name>.sh file, zero orchestrator changes - proven by the 10 plugins the orchestrator already runs today.
    Clean up after itself: seed_board only ever vault kv patches (merges), never deletes; nothing to clean up. No new artifact-store file.
    Frictionless for the owner: exactly one decision - the Bearings card below - carrying the one command to copy-paste; everything else (which keys, which values, the check afterward) is already decided in this design.
    Context discipline: this design reused three already-written documents (vault-seed-board.md, WO-20261019-b6b1, yieldpoint-ai.sh) rather than re-deriving the key list or the plugin shape from scratch.
    Multi-agent work, GOOD and NEVER examples: see GOOD and NEVER below.
    XML spec, mermaid architecture and DAG, the DAG is the source: dag.json is the source; mermaid generated by make dag-render.
    Migration is the test of the design: yp-dag.sh's node tooling proves this DAG migrates before any of REPO-REG/SEED-APP/CHECK is built from it.
    Config files and arguments pass every input: seed_board reads every value from an env var with a documented default (matching vault-seed-board.md's own re-seed command), never a literal baked into a conditional; host-* per tier has no default (required, owner-supplied) since those are not yet decided anywhere in the repo.
    Agent to agent is schema, never prose: REPO-REG/SEED-APP/CHECK are cut with the work-order skill, scripted ac_checks, never a prose brief; the owner-facing piece is a Bearings card, which is prose by design (item 12, item 18's own carve-out: "Prose is for the owner only").
    Small tickets, disjoint files, logical order: REPO-REG touches only claude/workflow/config/repos.json; SEED-APP touches only runbooks/vault-seed/seeds/apps/board.sh (+ its own test) in local-k8s-docs, depends_on REPO-REG; CHECK touches only a new script in this home. No two overlap.
    Worktree, feature branch, deterministic DAG path, the DAG is the state: REPO-REG/CHECK follow the no-repo-home convention; SEED-APP opens a real worktree/branch in local-k8s-docs (it is a real git repo with a GitHub remote, jkkelley/local-k8s-docs), which is exactly why REPO-REG must land first - wo_require_repos_resolve refuses approval of a ticket whose .repo is not in config/repos.json.
    Merge, never park: each of the three is its own small PR (SEED-APP) or no-repo direct close (REPO-REG, CHECK), never stacked.
    See it, isolate it, fix it, or hand it off and get out of the way: this design is itself the hand-off named by dispatch-ac-gate's own Goal ("the architect actions it directly") - it gives the architect and the owner the exact script and the exact card, so nobody has to improvise a vault kv patch by hand under pressure.
    Artifacts live outside git, named by script, linked in like packages: the Bearings card draft this design produces is written under ~/.local/state/zenith/card-drafts/2026/10/ (item 23's own naming convention), never into this repo.
    Smart checkpointing with compaction is the standard: unaffected - no new seat loop.
    No AWS spend beyond SSM and a justified S3 bucket: ssm_get calls in the orchestrator are read-only parameter reads the owner already pays for under minecraft-admin's existing, pre-approved SSM use (item 25's own carve-out) - board needs no new SSM parameter, since none of its 18 keys are secret-shaped (see Goal and scope).
    Producer and consumer, never push into a pane: not applicable - a one-shot script the owner runs in their own terminal, never piped into a seat's pane.
    One pattern for everything that watches: not applicable - no new monitor; the Argo Application health the check reads is already watched by the existing cluster dashboards, not re-implemented here.
    XML specs, contents list, mermaid, graceful recovery, idempotency, automation forever: vault kv patch is already idempotent (merge, not overwrite) - re-running seed_board twice is a no-op on the keys that already match; the check script is pure read, safe to re-run any number of times.
    Status codes, minimal prose, work orders all the way: see Status codes below (BVS-OK/BVS-NO-RESOURCES/BVS-AVP-ERROR/BVS-NOT-RUNNING); the owner's own card is the one deliberate exception to "schema, never prose" (item 18).
    Ape-sized work, scripted tests, everything up front: REPO-REG/SEED-APP/CHECK each carry their exact command/exit/expect at cut time; SEED-APP's one open freedom (whether host-* is read from a new env var or a new line in board-envs.json) is named explicitly as a degree of freedom, not left to guesswork.
    No evidence means the SOP was broken: every key and every status line below traces to a file already read in full (Inventory) - nothing is asserted from memory.
    Agents have no opinions: this design does not choose the real hostnames or decide to run the seed now - that choice is the owner's, carried on the card below, exactly as board-uat-seed/design.md's own precedent (owner approves before anything reaches a protected surface) already established for this same board.
    The architect may break glass to unstick the line: not applicable here - this design exists precisely so break-glass is never needed for this gap again; CHECK is what the architect runs instead of improvising a kubectl one-liner under pressure.
    Testing is promoted dev, then UAT, then stable: SEED-APP's own test runs against stubbed vault_exec/kubectl (dev only, per item 6 - no cluster is touched in CI); the real seed is inherently a one-shot dev-tier action per WO-20261019-b6b1's own Test plan ("dev tier only ... uat/stable follow once dev is proven, by the architect's own promotion decision").
    Testing never notifies the owner: neither test touches a board, a card or ntfy.
    The architect hotfixes missing permissions on the spot: not applicable - no missing permission was found while designing this; the permission boundary here (owner-only Vault write) is deliberate and stays exactly where it is.
    Time every process, and a slow one is a bottleneck: not applicable - a one-shot owner action and a sub-second read-only check, neither a recurring process to budget.
    Batch logically, push systematically: REPO-REG/SEED-APP/CHECK ship as one batch under this result, queued on the Bearings board after the batch 41 switch-hour card per this brief's own item 3 instruction.
    Processes run on the cluster, not on agents: the seed and the check both run outside the cluster (owner's terminal; architect's own kubectl context) by design - Vault write and credential handling are explicitly never a seat's or the cluster's job here (brief item 3: "seats never write Vault or the cluster, and agents never type, read or store credentials").
    The DAG is effortless to change, with a migration plan for every change: a changed key set (the chart gains a 19th AVP placeholder) is one seed_board/verify_board edit plus a dag-node-update; see Migration plan.


    THIS IS WHAT IS SHOWN TO USER, REAL SPEC BOOKS ARE IN XML



====


THAT CONTENT LIST APPLIES AT EACH LAYER AND MORE, I SHOULD BE ABLE TO ZOOM IN AND OUT OF THIS COMPANY BY LAYER AND SEE THE SAME PROCESSES WORKING LAYER BY LAYER


AS FAR AS PRODUCTS GO
---
WE SELL SECURITY AUDIT LOCAL | CLOUD | MULTI-CLOUD
COST OPTIMAZATION CLOUD AND BUSINESS
SETTING UP LLMS FOR COMPANIES PRODUCTS
SET UP INTERNAL/EXTERNAL LLMS FOR COMPANY TOOLING
INTEGRATIONS OF ALL KINDS
WORKFLOWS ALL KINDS OF WORK STREAMS (WE CREATE ALL)
SETTING UP CLOUD (COMMERICAL AND CLOUD)
CREATE APPLIATIONS/TOOLING/HOSTING
CREATE AI WORKFLOWS
CREATE SKILLS
CREATE AGENTS
CREATE AUTOMATION
CLOUD/AI CONSULTING
K8S EVERYTHING (ANY NEED WE SOLVE AND HELP WITH)
---


WE NEED TO FIGURE OUT OUR BUSINESS MODEL AND HOW TO SELL OUR PRODUCTS AND TURN THINGS INTO SUBSCRIPTIONS AND PRODCUTS THAT CAN BE SOLD, WE NEED TO HURRY ON THIS, THE PRODUCT DRIVES THE BUSINESS, THE PRODUCT DRIVES THE SALES CALLS, THE PRODUCT DRIVES EVERYTHING

I NEED THE COMMS BETWEEN JEV AND I SET UP AND WORKING ASAP, ITS MY FRONT DOOR INTO THE WHOLE OPERATION, IT TRIGGERS THE PROPER FLOW I NEED

WORKSTREAMS OF THE BUSINESS NEED TO BE ABLE TO BE HALTED AND SHIFTED EASILY AND PIVOTED
WE SHOULD KEEP SMART DOCUMENTATION OF WHATS BEING BUILT
WORK SHOULD HAVE PRIORITES, SMART LOGIC AND QUEUING FROM THE BEGINNING, PARALLELISM WHEN WE CAN, BUT MINDFUL OF RESOURCES, THEY'RE FINITE
CPU/MEMORY/MONEY NEVER GROW ON TREES


dotfiles has the skill work-orders/project-scaffold/context-compaction/container-sandbox

use the idea's behind them, but keep speed and efficiency in mind, they drop files in repos, we don't want that, we want artifacts outside and we want one agent, one file with that proper frontmatter and schema scripts without agent prose and it driven by a script or automation.

our command and control dashboard should like a bunch of images i'll send after this prompt, you'll need to logicially think about all this shit and how to get it done in the best way, fucking hell

Ensure we have logical storage locations for evidence too
when testing happens and it needs to kick back
screenshots, errors, anything evidence wise to re-produce the error, if you can't prove it, it didn't happen, we need evidecne and runbooks and systematic steps to give to agents on how to capture it and document it and pass it up with their blocked or run into this scenario

scroll thru C:\Users\jkkel\Pictures\Screenshots and you'll see some images of how the app was looking and feeling, the chat, etc, the branding, i want 

Everything thing besides user facing needs to be UTC for time capture, just show it to user in CST visually


THE BOARD APP THAT SERVED AT THE CMD AND CONQUER BOARD FOR ME, THE ADMIN SHIP
IT USED TAILSCALE TO SERVE IT, SO WE GOT VPN RIGHT FROM THE START AND THE APP WAS FOR ME
ITS NEED A REAL FRONTEND
REAL BACKEND DEVELOP IT AGAIN LIKE SO
GET THE UPLOAD VIDEO/IMAGE IN THE CHAT WORKING FIRST
BE LOGICAL ABOUT IT, DO ALL THE MAGIC BEHIND THE SCENES FOR THE VIDEO PROCESS AND COMPRESS AND TRANSCODING, DO MULTILANE SO ITS AVAILABLE TO USER RIGHT AWAY AND THEN GET ORIGINAL COPY FORMAT TOO
I HAVE TONS OF PICTURES ON THE C DRIVE OF WINDOWS OF THIS APPLICATION, I'LL SEND MORE

THE CHAT FUNCTIONALITY IS THE MOST IMPORTANT PART, WELL TAHT AND THE ABILITY TO ASK THE USER QUESTIONS RANGING FROM DESIGN TO WHATEVER TO LOCK IN SPECS

THE BEARINGS-V2 AND, RIME, LOCAL-K8S-DOCS ALL HAD THE BEARINGS APP, OR SOME VERSION OF IT, JUST VERSIONS OF IT PREVIOUS TO THE ONE WE LOST

WE'RE GOING TO BUILD IT RIGHT FROM THE BEGINNING
```
