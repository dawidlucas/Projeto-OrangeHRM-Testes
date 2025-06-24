# Casos de Teste - Tela de Login

| ID  | Caso de Teste                             | Passos                                                   | Resultado Esperado                         | Status |
|-----|-------------------------------------------|----------------------------------------------------------|---------------------------------------------|--------|
| CT01| Login com dados válidos                   | Digitar "Admin" e "admin123", clicar em Login            | Redireciona para o painel                   | ✅ Passou |
| CT02| Login com usuário inválido                | Digitar "Adminx" e "admin123", clicar em Login           | Mensagem: Invalid credentials               | ✅ Passou |
| CT03| Login com senha inválida                  | Digitar "Admin" e "senhaerrada", clicar em Login         | Mensagem: Invalid credentials               | ✅ Passou |
| CT04| Login sem preencher campos                | Deixar campos vazios e clicar em Login                   | Mensagem de erro "Invalid credentials" | ✅ Passou |


