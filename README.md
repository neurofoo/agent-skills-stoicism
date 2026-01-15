# Stoic Skills for Claude

A collection of 9 Stoic philosophy skills for Claude Code that help with emotional resilience, rational thinking, and cultivating wisdom.

## Installation

```bash
# Add the marketplace
/plugin marketplace add neurofoo/agent-skills-stoicism

# Install the skills
/plugin install stoic-skills@agent-skills-stoicism
```

## Skills

### Atomic Skills

| Skill | Description |
|-------|-------------|
| `/dichotomy-of-control` | Recognize what's in your control vs. what isn't. Use when feeling anxious, frustrated, or helpless about events. |
| `/premeditatio-malorum` | Negative visualization - imagine potential misfortunes to build resilience. Use when preparing for challenges or feeling anxious about the future. |
| `/voluntary-discomfort` | Intentionally practice mild hardship to build fortitude. Use during stable periods to toughen yourself for future challenges. |
| `/view-from-above` | Gain cosmic perspective by mentally zooming out. Use when overwhelmed, angry about small things, or needing humility. |
| `/memento-mori` | Reflect on mortality to clarify priorities. Use when procrastinating, dwelling on petty conflicts, or needing clarity about what matters. |
| `/amor-fati` | Love your fate - embrace whatever happens. Use when facing unwanted outcomes, setbacks, or feeling "why me?" |
| `/cognitive-reframing` | Examine and reframe negative impressions. Use when strong emotions (anger, fear, hurt) arise from your judgments about events. |

### Meta-Skills (Composite)

| Skill | Components | Description |
|-------|------------|-------------|
| `/prepare-for-adversity` | premeditatio-malorum + voluntary-discomfort | Comprehensive resilience training combining visualization and practice. |
| `/embrace-fate` | dichotomy-of-control + amor-fati | Full acceptance workflow: first discern what's controllable, then wholeheartedly embrace reality. |

## Usage Examples

**Feeling anxious about a job interview:**
```
/premeditatio-malorum
```
Claude will guide you through visualizing potential challenges and mentally preparing for them.

**Angry about something someone said:**
```
/cognitive-reframing
```
Claude will help you examine your interpretation and find a calmer perspective.

**Want comprehensive resilience training:**
```
/prepare-for-adversity
```
Claude will guide you through both negative visualization and voluntary discomfort exercises.

## How It Works

Each skill supports two modes:
- **Interactive Guide**: Claude walks you through the Stoic exercise step-by-step
- **Conceptual Reference**: Claude explains the philosophical principle for discussion

## Sources

Based on classical Stoic teachings from Epictetus, Seneca, and Marcus Aurelius. Structured from "Structured Stoic Skills for Claude" (included in repo).

## License

MIT
