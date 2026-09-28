# Resume and interview selection

These bullets describe portfolio artifacts developed with substantial AI assistance. Use only after personally running the demonstration and being able to explain the implementation. They are not employment or adoption claims.

## Projects to emphasize by role

| Role | Recommended focus | Why |
|---|---|---|
| Software engineering | NoteMesh, LinkScope, Upstream Lab | Concurrency, transactions, validation and a reproducible regression patch |
| Data science | Retention Studio, PayLens, CourtCraft | Operational decisions, baselines, calibration and uncertainty |
| AI / ML engineering | DocSearch Atlas, Ticket Tuner, EvalBench | Retrieval, real fine-tuning and inspectable evaluation |
| Cloud / DevOps | Shipyard, Network Foundry, Scale Lab | Container delivery, infrastructure testing and observed autoscaling |
| Data analytics | Margin Ledger, JourneyMark, Energy Brief | SQL correctness, attribution assumptions and reproducible public-data research |

Choose two or three for each application. Read the limitations and complete one independent exercise before an interview.

## Evidence-based project bullets

### [LinkScope](https://github.com/abhijith-abhii/linkscope)

- Built a transactional SQLite URL shortener with expiring aliases, aggregate click analytics and spreadsheet-safe CSV export; verified 15 regression and API checks.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/linkscope/blob/main/LEARNING_GUIDE.md)

### [NoteMesh](https://github.com/abhijith-abhii/notemesh)

- Implemented SSE synchronization and revision-based conflict detection for shared notes; verified two-tab synchronization and preservation of rejected drafts.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/notemesh/blob/main/LEARNING_GUIDE.md)

### [Repo Radar](https://github.com/abhijith-abhii/repo-radar)

- Built a cached GitHub activity explorer with bounded pagination and explicit sample/live modes; validated a real public API snapshot of 300 commits.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/repo-radar/blob/main/LEARNING_GUIDE.md)

### [TabHarbor](https://github.com/abhijith-abhii/tabharbor)

- Built a Manifest V3 tab organizer with domain grouping, duplicate review, workspaces and focus alarms; verified 15 local checks and actual Chromium API workflows in CI.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/tabharbor/blob/main/LEARNING_GUIDE.md)

### [Upstream Lab](https://github.com/abhijith-abhii/upstream-lab)

- Prepared a reproducible python-slugify CLI validation patch with ten passing regression cases and a 125-pass upstream suite; contribution remains unsubmitted.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/upstream-lab/blob/main/LEARNING_GUIDE.md)

### [PayLens](https://github.com/abhijith-abhii/paylens)

- Developed a synthetic salary regression workflow with disjoint training, calibration and test splits; measured $10,142 holdout MAE against a $22,305 median baseline.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/paylens/blob/main/LEARNING_GUIDE.md)

### [Retention Studio](https://github.com/abhijith-abhii/retention-studio)

- Extended an AI-assisted churn review application with a capacity-limited action queue, cooldown rules and audit history; verified fresh bootstrap and 27 tests on fictional telecom data.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/retention-studio/blob/main/LEARNING_GUIDE.md)

### [CourtCraft](https://github.com/abhijith-abhii/courtcraft)

- Implemented per-minute basketball comparisons and Gamma-Poisson shrinkage with uncertainty intervals on a transparent synthetic 24-player dataset.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/courtcraft/blob/main/LEARNING_GUIDE.md)

### [Ticket Tuner](https://github.com/abhijith-abhii/ticket-tuner)

- Fine-tuned FLAN-T5-small locally for three support-routing labels with template-family holdouts; measured macro F1 of 1.0 on 72 limited synthetic test examples.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/ticket-tuner/blob/main/LEARNING_GUIDE.md)

### [SpendMap](https://github.com/abhijith-abhii/spendmap)

- Built an editable-rule spending dashboard with integer-cent reconciliation and standardized customer clustering, including silhouette diagnostics on synthetic transactions.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/spendmap/blob/main/LEARNING_GUIDE.md)

### [DocSearch Atlas](https://github.com/abhijith-abhii/docsearch)

- Extended an incremental SQLite FTS5 document assistant with source-linked retrieval and optional local FLAN generation; verified 19 checks and an actual model response.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/docsearch/blob/main/LEARNING_GUIDE.md)

### [QueryGuard](https://github.com/abhijith-abhii/queryguard)

- Built a five-intent natural-language sales interface using parameterized SQL, read-only authorization and execution limits; verified 15 correctness and rejection checks.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/queryguard/blob/main/LEARNING_GUIDE.md)

### [Release Pilot](https://github.com/abhijith-abhii/release-pilot)

- Built a bounded release-review agent that runs local tests, blocks failing changes and audits generated summaries; added a fallback after observing unsupported model wording.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/release-pilot/blob/main/LEARNING_GUIDE.md)

### [EvalBench](https://github.com/abhijith-abhii/evalbench)

- Evaluated actual local FLAN outputs under two prompt strategies using exact match, token F1, coverage validation and paired bootstrap intervals across twelve authored cases.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/evalbench/blob/main/LEARNING_GUIDE.md)

### [ShelfMatch](https://github.com/abhijith-abhii/shelfmatch)

- Implemented weighted text-and-image product ranking using TF-IDF, color and texture features over sixteen original procedural swatches; verified twelve checks.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/shelfmatch/blob/main/LEARNING_GUIDE.md)

### [Shipyard](https://github.com/abhijith-abhii/shipyard)

- Delivered a non-root containerized service through GitHub Actions, with a read-only runtime, health and functional smoke checks, and captured temporary-deployment evidence.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/shipyard/blob/main/LEARNING_GUIDE.md)

### [Network Foundry](https://github.com/abhijith-abhii/aws-network-infrastructure-troubleshooting-lab)

- Validated segmented AWS network infrastructure with Terraform, twelve mock-provider checks and sixteen Python checks; documented diagnostics without provisioning paid resources.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/aws-network-infrastructure-troubleshooting-lab/blob/main/LEARNING_GUIDE.md)

### [CostCompass](https://github.com/abhijith-abhii/costcompass)

- Built a synthetic AWS billing analyzer with decimal reconciliation, tag-coverage reporting and median-based anomaly flags; separated hypothetical savings from measured costs.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/costcompass/blob/main/LEARNING_GUIDE.md)

### [Failover Forge](https://github.com/abhijith-abhii/failover-forge)

- Built a reproducible local failure-injection harness that terminates an owned primary HTTP process, measures client fallback and records restart observations.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/failover-forge/blob/main/LEARNING_GUIDE.md)

### [Scale Lab](https://github.com/abhijith-abhii/scale-lab)

- Configured a Kubernetes worker with resource requests, probes and HPA; observed a disposable CI cluster scale from two to six available replicas under load.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/scale-lab/blob/main/LEARNING_GUIDE.md)

### [Margin Ledger](https://github.com/abhijith-abhii/margin-ledger)

- Created eight SQLite business reports with order/line grain controls, return reversals and monetary reconciliation; published reproducible synthetic-data findings.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/margin-ledger/blob/main/LEARNING_GUIDE.md)

### [JourneyMark](https://github.com/abhijith-abhii/journeymark)

- Compared four marketing attribution models with lookback and repeat-conversion boundaries; verified credit conservation including unattributed conversion value.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/journeymark/blob/main/LEARNING_GUIDE.md)

### [Retail Control Tower](https://github.com/abhijith-abhii/retail-supply-chain-control-tower)

- Extended an existing supply-chain repository with a filtered business dashboard, distinct-order delivery metrics and field-level privacy checks on synthetic data.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/retail-supply-chain-control-tower/blob/main/LEARNING_GUIDE.md)

### [Experiment Lens](https://github.com/abhijith-abhii/experiment-lens)

- Built a 4,000-user synthetic A/B analysis workflow with sample-ratio checks, conversion intervals, lift estimates and power planning; verified nine analytical/API checks.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/experiment-lens/blob/main/LEARNING_GUIDE.md)

### [Energy Brief](https://github.com/abhijith-abhii/energy-brief)

- Published a reproducible electricity-generation report across six countries using a pinned 150-row OWID subset, verified checksums and explicit missing-data and unit handling.
- [Demonstration, decisions and five interview answers](https://github.com/abhijith-abhii/energy-brief/blob/main/LEARNING_GUIDE.md)

