# NexusOrch

Plataforma de orquestração IA para sistemas multi-agentes.

## Recursos

- Orquestração de agentes IA
- Integração com diversos LLMs
- Sistema de memória persistente
- Interface web para monitoramento
- APIs extensíveis

## Instalação

```bash
pip install nexusorch
```

## Uso Rápido

```python
from nexusorch import NexusOrch

nexus = NexusOrch()
nexus.add_agent("researcher", "gpt-4")
nexus.add_agent("planner", "claude-3")
nexus.add_tool("web_search")

result = nexus.run("Pesquise sobre mudanças climáticas e elabore um plano de ação")
print(result)
```

## Documentação

Para documentação completa, visite [docs/README.md](docs/README.md).

## Licença

MIT
