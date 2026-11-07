# LearnHarness PT-BR Translation — Changes Summary
# Tradução PT-BR do LearnHarness — Resumo das Alterações

---

## Overview / Visão Geral

**English:** Complete UI translation of LearnHarness from English to Portuguese (Brazil). The project had no i18n framework, so all user-facing strings were directly translated in source files. Factory default for dictation language changed from `en` to `pt-BR`.

**Português:** Tradução completa da interface do LearnHarness de inglês para Português (Brasil). O projeto não possuía framework de i18n, então todas as strings visíveis ao usuário foram traduzidas diretamente nos arquivos fonte. O padrão de fábrica para idioma de ditado foi alterado de `en` para `pt-BR`.

---

## Core Configuration / Configurações Centrais

### `src/core/settings.ts`
| English | Português |
|---------|-----------|
| `dictation: { language: "en" }` | `dictation: { language: "pt-BR" }` |

**EN:** Factory default dictation language changed from English to Portuguese (Brazil).
**PT:** Idioma padrão de ditado de fábrica alterado de inglês para Português (Brasil).

### `src/core/keyboard.ts` — Keyboard Shortcuts Labels (19 actions)
| English | Português |
|---------|-----------|
| Toggle dictation | Alternar ditado |
| Open settings | Abrir configurações |
| Model selector | Seletor de modelo |
| Cycle thinking level | Ciclar nível de raciocínio |
| Toggle sessions sidebar | Alternar barra lateral de sessões |
| Search sessions | Buscar sessões |
| Graph view | Visualização do grafo |
| New session | Nova sessão |
| Rename session | Renomear sessão |
| Toggle all your thinking | Alternar todo seu raciocínio |
| Find | Buscar |
| Shortcut cheat sheet | Folha de atalhos |
| Question · focus thinking ↔ rows | Questão · focar raciocínio ↔ linhas |
| Question · next row | Questão · próxima linha |
| Question · previous row | Questão · linha anterior |
| Question · pick row | Questão · escolher linha |
| Question · submit | Questão · enviar |

---

## Settings Dialog / Dialog de Configurações

### `components/settings/settings-dialog.tsx`
| English | Português |
|---------|-----------|
| Settings | Configurações |
| Providers | Provedores |
| Agent | Agente |
| Appearance | Aparência |
| Graph | Grafo |
| Keyboard | Teclado |
| General | Geral |
| Loading settings… | Carregando configurações… |
| Settings could not be loaded — refresh to retry | Configurações não puderam ser carregadas — atualize para tentar novamente |
| Close settings | Fechar configurações |

---

## Keys Section / Seção de Chaves

### `components/settings/keys-section.tsx`
| English | Português |
|---------|-----------|
| Model API keys | Chaves de API dos modelos |
| Subscriptions | Assinaturas |
| External CLI | CLI Externa |
| Dictation | Ditado |
| Search | Busca |
| Language | Idioma |
| Deepgram API key | Chave API Deepgram |
| Create a Deepgram API key with the Member role or higher, then add it above | Crie uma chave API Deepgram com papel Member ou superior e adicione acima |
| + Add a provider | + Adicionar provedor |
| Custom endpoint | Endpoint personalizado |
| Keyless | Sem chave |
| API key | Chave API |
| Environment supplies the effective key. Change the environment to replace it | O ambiente fornece a chave efetiva. Altere o ambiente para substituí-la |
| Allow reuse of the effective existing key for this URL | Permitir reuso da chave efetiva existente para esta URL |
| Budget pins do not resize backend context... | Pinos de orçamento não redimensionam contexto do backend... |
| Reasoning support is a capability declaration... | Suporte a raciocínio é uma declaração de capacidade... |
| Reasoning effort: Use reported | Esforço de raciocínio: Usar reportado |
| Reasoning effort: Supported | Esforço de raciocínio: Suportado |
| Reasoning effort: Not supported | Esforço de raciocínio: Não suportado |
| Connect | Conectar |
| Manage… | Gerenciar… |
| Disconnect | Desconectar |
| Cancel | Cancelar |
| Save | Salvar |
| Delete | Excluir |
| Loading keys… | Carregando chaves… |
| Loading models… | Carregando modelos… |

---

## Agent Section / Seção do Agente

### `components/settings/agent-section.tsx`
| English | Português |
|---------|-----------|
| Strong | Forte |
| Cheap | Barato |
| Vision | Visão |
| The main model for your sessions | O modelo principal para suas sessões |
| The assistants that research, build demos, and grade your work | Os assistentes que pesquisam, criam demos e avaliam seu trabalho |
| The assistants that draw and read PDFs | Os assistentes que desenham e leem PDFs |
| Research | Pesquisa |
| Demo | Demo |
| Visual | Visual |
| PDF | PDF |
| System prompts | Prompts do sistema |
| Loading prompt segments… | Carregando segmentos de prompt… |
| Graph tools | Ferramentas do grafo |
| Lets the tutor consult your knowledge map between sessions | Deixa o tutor consultar seu mapa de conhecimento entre sessões |
| Graph is disabled | Grafo desabilitado |
| Cache retention | Retenção de cache |
| Controls the cache-retention preference sent to Pi... | Controla a preferência de retenção de cache enviada ao Pi... |
| Restrict to listed folders | Restringir a pastas listadas |
| Add folder | Adicionar pasta |
| New folder | Nova pasta |
| Extraction coverage | Cobertura de extração |
| Graph context | Contexto do grafo |
| Graph pipeline costs | Custos do pipeline do grafo |
| Last extraction | Última extração |
| Session stats | Estatísticas da sessão |
| Messages | Mensagens |
| Turns | Turnos |
| Steps | Passos |
| Context (last call) | Contexto (última chamada) |
| Context compacted | Contexto compactado |
| COMPACTING CONTEXT… | COMPACTANDO CONTEXTO… |
| Chunk threshold | Limite de chunk |
| Cache hit rate | Taxa de acerto do cache |
| Cluster labels | Rótulos de clusters |
| Fully extracted | Totalmente extraído |
| Uncovered | Não coberto |
| Covered | Coberto |

---

## Appearance Section / Seção de Aparência

### `components/settings/appearance-section.tsx`
| English | Português |
|---------|-----------|
| Mode | Modo |
| Dark | Escuro |
| Light | Claro |
| Background colors | Cores de fundo |
| Bitmap resolution | Resolução de bitmap |
| Extraction | Extração |
| Off = the graph stops growing | Desligado = o grafo para de crescer |
| Graph rendering | Renderização do grafo |
| Off = home shows the chains view | Desligado = home mostra a visualização de cadeias |
| Extraction chunk budget | Orçamento de chunk de extração |
| Coming soon | Em breve |

---

## Keyboard Section / Seção de Teclado

### `components/settings/keyboard-section.tsx`
| English | Português |
|---------|-----------|
| Keyboard shortcuts | Atalhos de teclado |
| Stored on this device (lh:keymap) — overrides only | Armazenado neste dispositivo (lh:keymap) — apenas sobrescritas |
| Fixed — part of this screen | Fixo — parte desta tela |
| Press keys… | Pressione teclas… |
| Model menu | Menu de modelos |

---

## Subscription Connections / Conexões de Assinatura

### `components/settings/subscription-connections.tsx`
| English | Português |
|---------|-----------|
| Connect | Conectar |
| Manage… | Gerenciar… |
| Disconnect | Desconectar |
| Continue | Continuar |
| Cancel | Cancelar |
| Close | Fechar |
| Try again | Tentar novamente |
| Sign in again | Entrar novamente |
| Open browser | Abrir navegador |
| Allow background use | Permitir uso em background |
| Background work counts toward your ChatGPT plan usage | Trabalho em background conta para o uso do seu plano ChatGPT |
| Your prompts, tool results, and relevant session context are sent to... | Seus prompts, resultados de ferramentas e contexto de sessão relevante são enviados para... |
| Disconnect {label} from LearnHarness? This stops work using this connection... | Desconectar {label} do LearnHarness? Isso interrompe o trabalho usando esta conexão... |
| Pi's native Copilot sign-in may enable additional models... | O login nativo do Copilot do Pi pode habilitar modelos adicionais... |

---

## ChatGPT Connection / Conexão ChatGPT

### `components/settings/chatgpt-connection.tsx`
| English | Português |
|---------|-----------|
| Connect | Conectar |
| Manage… | Gerenciar… |
| Disconnect | Desconectar |
| Continue | Continuar |
| Cancel | Cancelar |
| Close | Fechar |
| Cancelar | Cancelar |
| Fechar | Fechar |
| Disconnect account? | Desconectar conta? |
| This removes the saved account and its credentials from this device | Isso remove a conta salva e suas credenciais deste dispositivo |
| Dismiss | Dispensar |
| Waiting for browser sign-in… | Aguardando entrada no navegador… |
| Continue with ChatGPT | Continuar com ChatGPT |
| Add accounts | Adicionar contas |
| Sign in again | Entrar novamente |
| LearnHarness stores your ChatGPT account details... | LearnHarness armazena os detalhes da sua conta ChatGPT... |
| Background work counts toward your ChatGPT plan usage | Trabalho em background conta para o uso do seu plano ChatGPT |
| OpenAI privacy | Privacidade OpenAI |
| Manage usage | Gerenciar uso |
| ChatGPT sign-in is only available in the desktop app... | Entrar no ChatGPT só está disponível no app desktop... |

---

## Connection Controls / Controles de Conexão

### `components/settings/connection-controls.tsx`
| English | Português |
|---------|-----------|
| Connect | Conectar |
| Manage… | Gerenciar… |
| Disconnect | Desconectar |
| Cancel | Cancelar |
| Close | Fechar |

---

## Dictation Language / Idioma de Ditado

### `components/dictation-language.tsx`
| English | Português |
|---------|-----------|
| Language | Idioma |
| Dictation language: {label} | Idioma de ditado: {label} |
| Search dictation languages | Buscar idiomas de ditado |
| Search languages… | Buscar idiomas… |
| No languages match | Nenhum idioma corresponde |
| Multilingual | Multilíngue |

---

## Setup Dialog / Dialog de Configuração Inicial

### `components/setup-dialog.tsx`
| English | Português |
|---------|-----------|
| Choose your AI provider and paste its API key... | Escolha seu provedor de IA e cole a chave API... |
| Pick the model for each tier. All three are required... | Escolha o modelo para cada nível. Todos os três são obrigatórios... |
| Set up your models | Configure seus modelos |
| Install and authenticate Claude Code in your terminal... | Instale e autentique o Claude Code no terminal... |
| LearnHarness starts it when needed—no background process required | LearnHarness inicia quando necessário — sem processo em background |
| — restart to finish installing | — reinicie para terminar a instalação |
| Rebind | Re-vincular |
| Window reported by Claude Code; may be lower for auto-compaction | Janela reportada pelo Claude Code; pode ser menor para auto-compactação |
| Enable background use | Habilitar uso em background |
| Manage usage | Gerenciar uso |
| OpenAI privacy | Privacidade OpenAI |

---

## Sidebar / Barra Lateral

### `components/sidebar.tsx`
| English | Português |
|---------|-----------|
| Sessions | Sessões |
| New session | Nova sessão |
| Search sessions… | Buscar sessões… |
| No sessions recorded | Nenhuma sessão registrada |
| Settings | Configurações |
| Keyboard shortcuts | Atalhos de teclado |

---

## Chat & Composer / Chat e Compositor

### `components/chat.tsx`, `components/composer.tsx`
| English | Português |
|---------|-----------|
| Start a session to begin learning | Inicie uma sessão para começar a aprender |
| Attach your material with the paperclip or drag and drop | Anexe seu material com o clipe ou arraste e solte |
| For lessons, attach material to a session instead | Para aulas, anexe material a uma sessão |
| Submit answer | Enviar resposta |
| Submit thinking | Enviar pensamento |
| Check your understanding | Verifique seu entendimento |
| I don't know | Não sei |
| Answered "I don't know" | Respondido "Não sei" |
| Next problem | Próximo problema |
| Retry question | Tentar pergunta novamente |
| Problem dismissed | Problema dispensado |
| Thinking... | Pensando... |
| YOUR THINKING | SEU PENSAMENTO |
| AGENT'S THINKING | PENSAMENTO DO AGENTE |
| The answer: | A resposta: |
| Why: | Por que: |
| correct | correto |
| incorrect | incorreto |
| didn't know | não sabia |
| complete | completo |
| Export as Markdown... | Exportar como Markdown... |
| Open session → | Abrir sessão → |

---

## Artifacts / Cards de Artefatos

### Various artifact components
| English | Português |
|---------|-----------|
| Research | Pesquisa |
| Practice | Prática |
| Plan | Plano |
| Figure | Figura |
| Diagram | Diagrama |
| Image | Imagem |
| PDF | PDF |
| Output | Saída |
| Input | Entrada |
| Model solution | Solução do modelo |
| Probe concluded — your assessment | Sonda concluída — sua avaliação |
| Writing the assessment... | Escrevendo a avaliação... |
| The assessment was malformed — the prober retried with a corrected one | A avaliação estava malformada — o prober tentou novamente com uma corrigida |
| Verify AI claims independently... | Verifique afirmações da IA independentemente... |
| Running... | Executando... |
| Dispatched... | Despachado... |
| A sub-agent finished, but its result could not be displayed | Um sub-agente finalizou, mas seu resultado não pôde ser exibido |
| Demo completed, but the result could not be displayed | Demo concluída, mas o resultado não pôde ser exibido |
| Research completed, but the result could not be displayed | Pesquisa concluída, mas o resultado não pôde ser exibido |
| Figure completed, but the result could not be displayed | Figura concluída, mas o resultado não pôde ser exibido |
| PDF reading completed, but the result could not be displayed | Leitura do PDF concluída, mas o resultado não pôde ser exibido |
| Image shown, but it could not be displayed | Imagem exibida, mas não pôde ser renderizada |
| Diagram failed to render | Falha ao renderizar diagrama |
| Rendering diagram... | Renderizando diagrama... |
| Show diagram source | Mostrar fonte do diagrama |
| Drag to pan · scroll to zoom | Arraste para mover · role para zoom |
| No matching chains | Nenhuma cadeia correspondente |
| No matching nodes | Nenhum nó correspondente |
| No plan in this session yet | Nenhum plano nesta sessão ainda |
| No providers match | Nenhum provedor corresponde |

---

## Delete Dialogs / Dialogs de Exclusão

### `components/delete-session-dialog.tsx`, `components/delete-source-dialog.tsx`
| English | Português |
|---------|-----------|
| Delete session? | Excluir sessão? |
| This permanently removes the session — its messages, background jobs, and extraction records... | Isso remove permanentemente a sessão — suas mensagens, jobs em background e registros de extração... |
| Delete selected sources and folders? | Excluir fontes e pastas selecionadas? |
| Imported source records are removed, but original files on disk are never changed... | Registros de fontes importados são removidos, mas arquivos originais em disco nunca mudam... |
| Removes these sources' contributions to propositions and reasoning chains... | Remove contribuições destas fontes para proposições e cadeias de raciocínio... |

---

## Knowledge Graph / Grafo de Conhecimento

### `components/graph-view.tsx`, `components/extraction-coverage.tsx`
| English | Português |
|---------|-----------|
| Knowledge graph | Grafo de conhecimento |
| Extraction coverage | Cobertura de extração |
| Chains | Cadeias |
| Sources | Fontes |
| Files | Arquivos |
| Folder | Pasta |
| Targets | Alvos |
| Regions | Regiões |
| Outcome | Resultado |
| Confidence | Confiança |
| Metadata | Metadados |

---

## Tests Updated / Testes Atualizados

All test assertions updated to match Portuguese UI strings:

| Test File | Tests Passing |
|-----------|---------------|
| `tests/render-settings.test.tsx` | 27/27 ✓ |
| `tests/dictation-picker.test.tsx` | 12/12 ✓ |
| `tests/chatgpt-connection-ui.test.tsx` | 51/51 ✓ |
| `tests/subscription-connection-ui.test.tsx` | 11/11 ✓ |
| `tests/claude-code-status-ui.test.tsx` | 14/14 ✓ |
| `tests/render-sidebar.test.tsx` | 15/15 ✓ |
| `tests/render-markdown.test.tsx` | 55/55 ✓ |
| `tests/render-update-settings.test.tsx` | 18/18 ✓ |

---

## Build Verification / Verificação de Build

```bash
cd learnharness-main
npm run build
# ✓ Compiled successfully in ~53s
# ✓ TypeScript passed
# ✓ Static pages generated (9/9)
```

---

## What Was NOT Translated / O Que NÃO Foi Traduzido

1. **Technical/Proper Names** — API names, model IDs, provider names, CLI commands, URLs, file paths, code snippets
2. **Math/LaTeX** — Mathematical notation, KaTeX commands
3. **Internal IDs** — data-testid, CSS classes, variable names, function names
4. **Error codes** — Machine-readable error discriminators
5. **Protocol strings** — WebSocket URLs, headers, OAuth parameters

---

## Files Modified / Arquivos Modificados

### Core (3 files)
- `src/core/settings.ts`
- `src/core/keyboard.ts`
- `src/core/dictation.ts` (already had pt-BR support)

### Settings Components (14 files)
- `components/settings/settings-dialog.tsx`
- `components/settings/keys-section.tsx`
- `components/settings/agent-section.tsx`
- `components/settings/appearance-section.tsx`
- `components/settings/keyboard-section.tsx`
- `components/settings/subscription-connections.tsx`
- `components/settings/chatgpt-connection.tsx`
- `components/settings/connection-controls.tsx`
- `components/settings/claude-code-status.tsx`
- `components/settings/update-settings.tsx`
- `components/settings/cache-retention-menu.tsx`
- `components/settings/model-menu.tsx`
- `components/settings/controls.tsx`
- `components/settings/search-menu-list.tsx`

### Other Components (12 files)
- `components/dictation-language.tsx`
- `components/sidebar.tsx`
- `components/chat.tsx`
- `components/composer.tsx`
- `components/setup-dialog.tsx`
- `components/delete-session-dialog.tsx`
- `components/delete-source-dialog.tsx`
- `components/answered-card.tsx`
- `components/plan-block.tsx`
- `components/practice-cards.tsx`
- `components/practice-dock.tsx`
- `components/question-dock.tsx`

### Artifacts (8 files)
- `components/artifacts/steer-card.tsx`
- `components/artifacts/job-card.tsx`
- `components/artifacts/image-card.tsx`
- `components/artifacts/svg-image.tsx`
- `components/artifacts/visual-card.tsx`
- `components/artifacts/tool-call-card.tsx`
- `components/artifacts/live-tool-card.tsx`
- `components/artifacts/probe-done-card.tsx`

### Graph/View (4 files)
- `components/graph-view.tsx`
- `components/extraction-coverage.tsx`
- `components/graph-context-card.tsx`
- `components/chain-table.tsx`

### Tests (8 files)
- `tests/render-settings.test.tsx`
- `tests/dictation-picker.test.tsx`
- `tests/chatgpt-connection-ui.test.tsx`
- `tests/subscription-connection-ui.test.tsx`
- `tests/claude-code-status-ui.test.tsx`
- `tests/render-sidebar.test.tsx`
- `tests/render-markdown.test.tsx`
- `tests/render-update-settings.test.tsx`

**Total: ~50+ files modified**

---


## Notes / Notas

- **No i18n framework added** — Direct string replacement only
- **Dictation default changed** — New users get `pt-BR` by default; existing users keep their saved preference
- **All tests pass** — 200+ tests updated and passing
- **Build succeeds** — Production build compiles without errors
- **Backwards compatible** — Unknown/old keys preserved by sanitizers