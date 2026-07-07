# seedance-prompt

Hermes skill for writing structured, realistic AI video prompts for Seedance, Sora, Kling, Runway, Veo, and similar text-to-video models.

This skill turns a vague scene idea into a high-density prompt with:

- source-footage identity
- camera/device aesthetics
- concrete location details
- time-coded shot progression
- natural audio cues
- anti-AI artifact checks

## Install manually

Copy this folder into your Hermes skills directory:

```bash
mkdir -p ~/.hermes/skills/creative
cp -a seedance-prompt ~/.hermes/skills/creative/seedance-prompt
```

Then verify:

```bash
hermes skills list | grep seedance-prompt
```

## Files

- `SKILL.md` - main Hermes skill
- `references/camera-aesthetics.md` - camera and device imperfection packs
- `references/atmosphere-dictionary.md` - maps abstract moods to concrete visual/audio phenomena
- `references/anti-ai-checklist.md` - common AI-video artifacts, negative constraints, and imperfect event library

## License

MIT
