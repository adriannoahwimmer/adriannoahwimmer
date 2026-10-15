# Hi, I'm Adrian

I'm a master's student in **Information Systems** at the **Karlsruhe Institute of Technology (KIT)**.
I work on machine learning for autonomous driving, LLM-based information extraction and Bayesian statistics.
Next to my studies I am building [MatchCrew](https://github.com/adriannoahwimmer/matchcrew-demo), my own marketplace app for amateur basketball.

## Selected projects

### Own product

- **[matchcrew-demo](https://github.com/adriannoahwimmer/matchcrew-demo)**: MatchCrew, a marketplace app that finds substitutes for game-day duties at the scorer's table in amateur basketball, starting in Karlsruhe.
  I own the product: requirements, business rules, architecture decisions and the acceptance test of every package on a real phone.
  The code is written agentically with Claude Code in a fixed workflow of plan, approval, pull request and merge on green CI.
  All MVP features except push notifications are done, and a closed beta is in preparation.
  The repo shows screenshots, the architecture and the roadmap; the [landing page](https://adriannoahwimmer.github.io/matchcrew-demo/) has a click demo.
  *Claude Code, Expo, React Native, TypeScript, Supabase*

### Autonomous driving

- **[maptr-aerial-fusion](https://github.com/adriannoahwimmer/maptr-aerial-fusion)**: Bachelor's thesis at KIT and FZI (2024/25).
  A transformer network fuses aerial images with the vehicle's camera images to build HD maps online.
  The thesis extends MapTR and improves its mAP on nuScenes from 0.470 to 0.484.
  *PyTorch*
- **[jbdata-opendrivevla](https://github.com/adriannoahwimmer/jbdata-opendrivevla)**: Runs the vision-language-action model OpenDriveVLA zero-shot on data recorded with the FZI research vehicle in Karlsruhe, then evaluates the predicted trajectories.
  This was a machine learning lab course at KIT.
  *PyTorch*

### LLMs and NLP

- **[email-action-chain-extraction](https://github.com/adriannoahwimmer/email-action-chain-extraction)**: Finds recurring workflows in email inboxes, with their actors, tasks and decision points, and quotes the emails as evidence.
  The pipeline groups related emails (embeddings, UMAP, HDBSCAN), extracts the workflows with an LLM and shows them in a web interface.
  This was a practical seminar at KIT.
  *Python*

### Statistics

- **[variational-bayes-nba-salaries](https://github.com/adriannoahwimmer/variational-bayes-nba-salaries)**: Compares mean-field variational Bayes (CAVI) with Gibbs sampling for Bayesian linear regression.
  Both methods are implemented from scratch and applied to 7,298 NBA player-seasons.
  This was a research seminar at KIT (2026).
  *R*

### Mixed reality

- **[xr-neural-net-visualizer](https://github.com/adriannoahwimmer/xr-neural-net-visualizer)**: A Unity app for Varjo headsets that places a small neural network in the room.
  You set its weights with hand-tracked sliders and watch the loss change live.
  This was a team project at KIT (2023/24).
  *C#, Unity*

### Other

- **[graph-algorithms-2022](https://github.com/adriannoahwimmer/graph-algorithms-2022)**: Graph algorithms from my exchange semester at Tampere University, Finland (2022): BFS shortest-path trees, Floyd–Warshall and minimum spanning trees.
  *Python*

## Tools

Python · PyTorch · R · C# / Unity
