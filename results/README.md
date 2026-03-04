# Workshop Results

Each subfolder is one participant's project, published to GitHub Pages at:

```
https://bauhaus-infau.github.io/ai-lab/<name>/
```

## Structure

```
results/
├── index.html      ← Landing page (auto-lists projects via GitHub API)
├── README.md       ← This file
├── alice/
│   └── index.html  ← Participant project (plain HTML or Vite build output)
├── bob/
│   └── ...
└── ...
```

## How projects get here

Participants follow **Part 5** of the [workshop guide](../workshop/README.md) to copy their built files into a subfolder, then open a pull request. The instructor merges it, and GitHub Actions deploys the updated `results/` folder to Pages.
