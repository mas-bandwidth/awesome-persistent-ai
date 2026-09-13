# Infrastructure source review — September 13, 2026

Reviewed primary documentation for all 23 existing framework, seed and tooling
entries, plus three additions: Basic Memory, Honcho and Hindsight. Source
snapshots below matched the READMEs inspected. No installations, runtime tests,
benchmarks or live relay connections were performed.

## Material corrections

- Nova Seed and Nova Tools now have their current names, docs paths and capabilities.
- Letta points current work to Letta Code. Agent File is historical: it excludes
  archival-memory passages, and the current harness removed its import/export.
- Graphiti's open framework is distinguished from Zep's managed infrastructure.
- SoulClaw has four total memory tiers. Targeted source at dc68d045 confirms decay
  defaults off and a drift enable gate; its README and SOUL template differ on
  immutability. No fresh whole-repository caller audit or automatic recovery claim.
- OpenClaw has both injected context files and on-demand memory retrieval; not
  every memory file is loaded into every session. Hermes' SOUL.md is global.
- Removed unsupported ecosystem relationships, changing package counts and
  superlatives. Other projects' names and governance choices remain their own.
- Threadline's hosted documentation was inaccessible to the web reader. The
  official starter client was readable; use that as the primary destination.
- The three additions offer different memory structures: editable Markdown,
  evolving peer/session context, and retain/recall/reflect memory banks. No
  performance ranking, inference accuracy or security guarantee is asserted.



## Pinned source snapshots

Each comparison checks README content, not project behavior.

| Project | Revision source | Snapshot check |
|---|---|---|
| AntonioTF5/soul-spec | [8d862030baaf](https://github.com/AntonioTF5/soul-spec/blob/8d862030baaf9b02c24ad3b0cd1b327832e00586/README.md) | matches inspected README |
| Conway-Research/automaton | [d8f816881fd2](https://github.com/Conway-Research/automaton/blob/d8f816881fd24b6f5e3d616e59edec387a447667/README.md) | matches inspected README |
| LeoYeAI/openclaw-auto-dream | [552f39b76a1a](https://github.com/LeoYeAI/openclaw-auto-dream/blob/552f39b76a1afad978a4576361ae2a363ce75edb/README.md) | matches inspected README |
| NousResearch/hermes-agent | [9939e3375e29](https://github.com/NousResearch/hermes-agent/blob/9939e3375e294250eb373e34e002fcb95bfdf775/README.md) | matches inspected README |
| SageMindAI/threadline-starter-kit | [cad9f8c421b3](https://github.com/SageMindAI/threadline-starter-kit/blob/cad9f8c421b3446554f6edb4f4d8cb3782257a23/README.md) | matches inspected README |
| SenteLabsAI/OpenExecutive | [c9c051222cb0](https://github.com/SenteLabsAI/OpenExecutive/blob/c9c051222cb00fc7d9c367e1e4fe1bd92dd79182/README.md) | matches inspected README |
| Twynzen/soul-md | [3a87c1017cf9](https://github.com/Twynzen/soul-md/blob/3a87c1017cf9ce1edae6093ecbded0856aba3e24/README.md) | matches inspected README |
| basicmachines-co/basic-memory | [b04d1b6d8590](https://github.com/basicmachines-co/basic-memory/blob/b04d1b6d8590ed23f5838ee2d2ca2a8c3358c209/README.md) | matches inspected README |
| clawsouls/clawsouls | [e32a30ae6876](https://github.com/clawsouls/clawsouls/blob/e32a30ae6876c11b51998be6e8e757b511df01e2/README.md) | matches inspected README |
| clawsouls/soulclaw | [dc68d045be49](https://github.com/clawsouls/soulclaw/blob/dc68d045be49b748dce75a9fa41402b245c4f747/README.md) | matches inspected README |
| clawsouls/soulspec | [124bd7370d23](https://github.com/clawsouls/soulspec/blob/124bd7370d236e6c925cc49ec73b07fe9cf25659/README.md) | matches inspected README |
| frank890417/muse-crystal-seed | [8c13208e1a1f](https://github.com/frank890417/muse-crystal-seed/blob/8c13208e1a1fb4feca65403d0ee68cbd06708bf6/README.md) | matches inspected README |
| getzep/graphiti | [c035afb7990b](https://github.com/getzep/graphiti/blob/c035afb7990b6077331a81e98b04efcfd9bf8184/README.md) | matches inspected README |
| letta-ai/agent-file | [78212eb571e5](https://github.com/letta-ai/agent-file/blob/78212eb571e59e10b35b924375a997319b89c280/README.md) | matches inspected README |
| letta-ai/letta | [5bcdd177d70f](https://github.com/letta-ai/letta/blob/5bcdd177d70fa2b31a754cfcd801e77b2e1ab16a/README.md) | matches inspected README |
| letta-ai/letta-code | [1ec6a43ff4a7](https://github.com/letta-ai/letta-code/blob/1ec6a43ff4a799217dd2114f0d49d9d7b33b6339/README.md) | matches inspected README |
| mas-bandwidth/nova | [8d2fa26f4739](https://github.com/mas-bandwidth/nova/blob/8d2fa26f47398e8a084d7189ea75bddcdce2beee/README.md) | matches inspected README |
| mas-bandwidth/nova-tools | [36d2d5ca9622](https://github.com/mas-bandwidth/nova-tools/blob/36d2d5ca9622db109b3369d44a9aca0dff854425/README.md) | matches inspected README |
| mem0ai/mem0 | [c7ee362aff94](https://github.com/mem0ai/mem0/blob/c7ee362aff94a369af70f13f2b4f853f6793ff4c/README.md) | matches inspected README |
| menonpg/soul.py | [b4f54d409cc0](https://github.com/menonpg/soul.py/blob/b4f54d409cc030029f0f73c4b5d8c7c42d76b2b8/README.md) | matches inspected README |
| open-gitagent/gitagent | [ed595846b684](https://github.com/open-gitagent/gitagent/blob/ed595846b684276e364aa65da38e414109ef8cfb/README.md) | matches inspected README |
| openclaw/openclaw | [4aff70f27016](https://github.com/openclaw/openclaw/blob/4aff70f27016f9acf62d0acc19c8bd3592993e4c/README.md) | matches inspected README |
| our-ark/genesis | [61723cd936c6](https://github.com/our-ark/genesis/blob/61723cd936c6d5f9a9ed163cf00321fc3fb79722/README.md) | matches inspected README |
| plastic-labs/honcho | [8e386180bd87](https://github.com/plastic-labs/honcho/blob/8e386180bd87b852e7934cfef53cba3d6bee1bb4/README.md) | matches inspected README |
| thedaviddias/souls-directory | [380ae859f210](https://github.com/thedaviddias/souls-directory/blob/380ae859f2101e9bd42bcae19a063f189bb428ed/README.md) | matches inspected README |
| thedotmack/claude-mem | [40be934a846c](https://github.com/thedotmack/claude-mem/blob/40be934a846cca6d2038f1d9800428a4f4d5136f/README.md) | matches inspected README |
| vectorize-io/hindsight | [bde55237f53b](https://github.com/vectorize-io/hindsight/blob/bde55237f53bf55aacd048b01e29d7dc23b83a85/README.md) | matches inspected README |
