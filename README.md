# DIKWP OpenClaw OS for DeepSeek V4

**DIKWP OpenClaw OS** is a portable semantic enhancement, audit and repair layer for DeepSeek V4 users. It is not a jailbreak tool and does not bypass account, quota, payment, safety, system prompt, or platform rules.

OpenClaw means **Open Cognitive Layer for Answering Workflows**. It uses a claw metaphor:

- **Left Claw**: compiles intent, evidence, residuals and boundaries before asking DeepSeek.
- **Right Claw**: audits, repairs and downgrades answers after DeepSeek responds.
- **Shell**: protects action boundaries, privacy and evidence discipline.
- **Heart**: runs an artificial-consciousness-inspired semantic homeostasis core.
- **Tail**: produces recovery prompts and fallback capsules.

## Install

```bash
pip install -e .
```

## Build a DeepSeek V4 attachment prompt

```bash
openclaw build examples/sample_deepseek_v4_task.json --out outputs/demo
```

## Audit an answer

```bash
openclaw audit examples/sample_deepseek_v4_answer.md --capsule outputs/demo/openclaw_capsule.json --out outputs/demo
```

## Static boundary audit

```bash
openclaw static-audit src --out outputs/demo/static_boundary_audit_report.json
```

## Output files

- `openclaw_capsule.json`
- `deepseek_v4_attachment_prompt.md`
- `micro_claw.txt`
- `api_payload_template_openai.json`
- `api_payload_template_anthropic.json`
- `route_plan.json`
- `ac_state_trace.json`
- `response_audit_report.json`
- `response_repair_plan.md`
- `trustpassport_seed.json`

## Boundary

OpenClaw improves semantic expression and answer auditing. It does not make DeepSeek correct, conscious, unrestricted, or policy-free.
