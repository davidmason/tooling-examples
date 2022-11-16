# Tooling Examples

During my 6 years on the Globalization Tools team at Red Hat all my work was open source, primarily on tooling used by translators and engineers (e.g. [Zanata](http://github.com/zanata) and [Zayf](https://github.com/davidmason/zayf)). Here are some examples:

- Created a lightweight API server with simulated latency to fix a pain point, allowing faster and more robust frontend development: [fake-zanata-server](https://github.com/zanata/fake-zanata-server).
- Turned Storybook into a tool my team could use for rapid component customization by combining addons [commit to Zanata Platform](https://github.com/zanata/zanata-platform/commit/30b993a7f6b380db6fa7cd6e654f44bfc6b09653)
- Updated redux-logger to support symbol types, which my team were using at the time: https://github.com/davidmason/redux-logger
- Patched React's update addon to maintain reference equality when possible: https://github.com/facebook/react/compare/main...davidmason:react:master
- Contributed to facebook/flow to fix a pain point my team were experiencing: https://github.com/facebook/flow/commit/84ae36d05049f31b1089c1fa33060a2b3ea4b8f8
- Implemented something similar to snapshot testing for React components to facilitate easy testing: https://github.com/davidmason/retap
- Gave a presentation in the Red Hat office to translators, writers and engineers breaking down the process of internationalising and localising software in an easy to follow way. The recording is not available, but the presentation followed the commits in this repo: https://github.com/davidmason/Hatter
- Automated sync of translations between Drupal and Zanata, eliminating a manual process for some of our users: https://github.com/zanata/tmgmt_zanata, made setup more streamlined: https://github.com/zanata/tmgmt_express_checkout, and made environment setup easy for the team: https://github.com/zanata/drupal_dev_environment
