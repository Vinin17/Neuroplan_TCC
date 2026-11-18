# NeuroPlan
APP PARA ORGANIZAÇÃO DE ROTINAS PARA PESSOAS NEURODIVERGENTES

**Acesse:** https://vinin17.github.io/Neuroplan_TCC/

Projeto de TCC feito com HTML, CSS e JavaScript puros, sem back-end.

## Funcionalidades

- Cadastro inicial em passos
- Tela **Hoje** com as tarefas do dia e da semana
- **Rotina** com calendário mensal
- Criar, editar e excluir tarefas
- **Cuidados**: pausas, modo calmo, sessões curtas e prioridade
- Perfil, tema claro/escuro e tamanho da fonte

## Checklist dos critérios

| Critério | Atende | Por quê |
|----------|:------:|---------|
| Deploy e funcionamento | ✅ | Publicado no GitHub Pages com `index.html` na raiz. Caminhos relativos para CSS, JS e imagens, sem dependências externas. |
| Interatividade sem recarregamento | ✅ | Os formulários usam `preventDefault()` e tudo é tratado em JavaScript. Concluir tarefas, calendário, perfil e configurações atualizam a tela sem recarregar. Ao salvar ou excluir uma tarefa, o app volta para a tela de destino com um aviso de confirmação. |
| Persistência de dados | ✅ | Tarefas, perfil, cuidados e configurações ficam no `localStorage` e continuam após o F5. Os avisos entre telas usam `sessionStorage`. |
| Estabilidade do console | ✅ | Sem chamadas a `console.*`, acessos ao storage dentro de `try/catch` e todos os arquivos referenciados existem no repositório. |
| Responsividade e acessibilidade | ✅ | Meta viewport e media queries para celular, tablet e desktop, sem rolagem horizontal. HTML semântico (`header`, `main`, `nav`, `h1`), `lang="pt-BR"`, `alt` nas imagens, `label` em todos os campos, `aria-label` nos ícones, `aria-live` e `role="alert"` nas mensagens. |

## Estrutura

```
├── index.html          Hoje
├── login.html          Cadastro inicial
├── rotina.html         Calendário
├── nova-tarefa.html    Criar e editar tarefa
├── cuidados.html       Cuidados
├── usuario.html        Perfil
├── configuracoes.html  Configurações
├── style.css
├── script.js
└── img/
```

## Privacidade

Os dados ficam só no navegador do usuário e podem ser apagados em Configurações.

## Autor

Vinícius Closs
