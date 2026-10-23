# Hyejin Kwon

Data scientist (machine learning), formerly at CERN on the CMS experiment. PhD in experimental particle physics, Seoul National University.

- **Rare-event classification.** Designed and trained a parameterized neural network (one model across 34 signal hypotheses) to find a very rare signal in highly imbalanced data → [ZpllMET](https://github.com/hjkwon260/ZpllMET) · [arXiv:2603.11035](https://arxiv.org/abs/2603.11035)
- **ML in production software.** As ML Production Group convener, coordinated and reviewed ML inference code in CMSSW, the C++ framework that processes all CMS data, and initiated the ML model metadata workflow for the conditions database → [all my CMSSW PRs](https://github.com/cms-sw/cmssw/pulls?q=is%3Apr+author%3Ahjkwon260) (including the metadata work)
- **Real-time trigger software.** Wrote the prototype of the default muon seeding algorithm in CMS's next-generation real-time event filter, now part of CMSSW → [L2MuonSeedGeneratorFromL1TkMu.cc](https://github.com/cms-sw/cmssw/blob/ac40c49f80aec3e1d65829e68f90ca898ff7c313/RecoMuon/L2MuonSeedGenerator/plugins/L2MuonSeedGeneratorFromL1TkMu.cc#L8) · [Phase-2 DAQ & HLT Technical Design Report, CMS-TDR-022](https://cms-results.web.cern.ch/cms-results/public-results/preliminary-results/TDR-21-001/index.html)
- **Efficiency measurement.** Extended the statistical fit model of CMS's tool for measuring electron identification efficiency, which produces the official corrections used across CMS → [cms-egamma/egm_tnp_analysis](https://github.com/cms-egamma/egm_tnp_analysis) · [my original PRs](https://github.com/lsoffi/egm_tnp_analysis/pulls?q=is%3Apr+author%3Ahjkwon260) · [JINST 16 P05014](https://doi.org/10.1088/1748-0221/16/05/P05014)
- **Data pipelines.** Maintained the trigger's online-to-offline condition database software (MySQL, Python, Go) and automated it with GitLab CI/CD → [my commits to cms-cactus/l1t-o2o](https://gitlab.cern.ch/cms-cactus/ops/l1t-o2o/-/commits/master_p5_cc8?author=Hyejin%20Kwon)

**Stack:** Python, C++, Go, SQL (MySQL), PyTorch, TensorFlow, XGBoost, scikit-learn, pandas, Docker, GitLab CI/CD
