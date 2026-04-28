I need to create a 15-second Manim video introducing zellij terminal multiplexer. Set up a team with this workflow:

## Critical: oh-my-opencode-slim Zellij Integration
**Use the built-in oh-my-opencode-slim zellij integration** instead of manual pane setup:

1. First, configure oh-my-opencode-slim to use zellij:
```bash
mkdir -p ~/.config/opencode
cat > ~/.config/opencode/oh-my-opencode-slim.json << 'EOF'
{
  "multiplexer": {
    "type": "zellij"
  }
}
EOF
```

2. Start opencode inside an existing zellij session with `--port 4096`: 
```bash
zellij
opencode --port 4096
This session should already be on 4096
```

3. When @explorer, @librarian, @fixer etc. are spawned, oh-my-opencode-slim will automatically create dedicated panes for each subagent in zellij

This is the correct "oh-my-opencode zellij multiplexer feature" - the integration handles it automatically!

## Phase 1: Research (parallel)
Each agent in their own zellij pane (auto-created by oh-my-opencode-slim) researches and writes to research/[topic].md:

1. @explorer - Research zellij: what it is, key features (layouts, floating panes, plugins, session management), use cases, how it compares to tmux/screen

2. @explorer - Research history of terminal multiplexers: tmux, screen, zellij evolution, why multiplexers matter, industry adoption

3. @librarian - Research Manim API: animation techniques, Text/Rectangle/Arrow creation, scene timing, colors, best practices for 15-30s videos

4. @explorer - Research opencode: capabilities of this AI coding orchestrator, delegation rules, available agents and when to use each

## Phase 2: Review (sequential after Phase 1)
5. @oracle - Review all research files, verify accuracy, identify gaps or contradictions across topics

6. @designer - As videographer: brainstorm visual approach for a 15-sec zellij intro video. Consider: color palette (zellij orange/rust theme), animation flow (title → panes → floating → features), pacing, key moments to highlight. Write visualization_plan.md with scene-by-scene breakdown

## Phase 3: Implementation
7. @fixer - Create the Manim video script in zellij-manim/ directory using findings from all research + visualization plan. Make it 15 seconds, render at 1080p, professional quality

## Output requirements:
- research/zellij.md
- research/multiplexers.md  
- research/manim_api.md
- research/opencode.md
- visualization_plan.md
- zellij_video.py with working Manim scene
- Rendered video file .mp4

## Execution:
1. Configure oh-my-opencode-slim.json with zellij multiplexer first
2. Start/opencode inside zellij session with --port
3. Launch research agents - panes will auto-appear
4. Then proceed to review and implementation phases
