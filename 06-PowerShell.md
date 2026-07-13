# 💻 Automação com PowerShell

O PowerShell é essencial para a eficiência operacional, permitindo a automação de tarefas repetitivas e a gestão ágil de infraestrutura.

## 🛠️ Comandos Úteis para o Dia a Dia
- **Verificar Status de Serviço:** `Get-Service -Name "NomeDoServiço"`
- **Reiniciar Serviço Remotamente:** `Get-Service -ComputerName "Server01" -Name "NomeDoServiço" | Restart-Service`
- **Listar Usuários Bloqueados no AD:** `Search-ADAccount -LockedOut`

## 📜 Scripts de Automação
### 1. Limpeza de Logs e Arquivos Temporários
Este script auxilia na manutenção preventiva de servidores de aplicação.
```powershell
$path = "C:\Logs"
$days = 30
Get-ChildItem $path -Recurse | Where-Object { $_.LastWriteTime -lt (Get-Date).AddDays(-$days) } | Remove-Item

---

### Passo 2: Criar o arquivo `07-Troubleshooting.md`
Aqui você aplica sua experiência com **ITIL e SLAs**. [5-7]

**Conteúdo para copiar:**
```markdown
# 🔍 Metodologia de Troubleshooting

Resolução de incidentes críticos focada em disponibilidade e continuidade de serviços em ambientes de alta criticidade. [2, 8]

## 📋 Fluxo de Análise (Baseado em ITIL)
1. **Identificação:** Coleta de evidências (prints, logs de erro, impacto no negócio).
2. **Diagnóstico:** Investigação via SQL Server e logs de APIs REST. [1, 9]
3. **Isolamento:** Diferenciar falha de infraestrutura, código ou integração de terceiros (SFTP/VPN). [10]
4. **Resolução:** Aplicação da correção e validação pós-produção.

## 🛠️ Ferramentas de Diagnóstico
- **Event Viewer:** Análise de logs do sistema e aplicativos.
- **SQL Profiler:** Identificação de queries lentas ou travamentos (Deadlocks).
- **Postman:** Testes de integração em APIs REST. [9, 11]
