
# Atividade: Integração e Entrega Contínua - Aula 2

Bem-vindos à atividade prática de controle de versão com Git! Nesta atividade, vamos explorar operações básicas de Git em um fluxo de trabalho colaborativo, incluindo criação de branches, commits, merges e resolução de conflitos.

---

## Objetivo
Praticar o uso de Git em equipe, realizando operações de clonagem, criação de branches, commits e merge, aplicando os conhecimentos sobre controle de versão avançado.

---

### Passo a Passo da Atividade

#### 1. Clonar o Repositório

Primeiro, cada aluno deve **clonar** este repositório para sua máquina local. No terminal, execute o seguinte comando:

```bash
git clone <URL_DO_REPOSITORIO>
```

Substitua `<URL_DO_REPOSITORIO>` pelo link HTTPS ou SSH do repositório.

#### 2. Criar um Branch para o Grupo

Cada grupo deve criar um branch com o nome `feature-grupoX`, onde `X` é o número do grupo (por exemplo, `feature-grupo1`).

No terminal, navegue até a pasta do repositório clonado e execute:

```bash
git checkout -b feature-grupoX
```

#### 3. Criar Arquivos Individuais

Cada integrante do grupo deve criar um arquivo com seu próprio nome (ex: `joao.md`, `maria.md`) dentro da pasta raiz do repositório. Neste arquivo, inclua uma breve descrição de sua área de interesse em tecnologia.

#### 4. Adicionar e Comitar Alterações

Após criar seu arquivo, adicione-o ao Git e faça um commit. Execute os seguintes comandos:

```bash
git add .
git commit -m "Adicionando arquivo pessoal de <SEU_NOME>"
```

Substitua `<SEU_NOME>` pelo seu nome.

#### 5. Fazer o Push do Branch para o Repositório Remoto

Envie seu branch para o repositório remoto no GitHub com o comando:

```bash
git push origin feature-grupoX
```

Certifique-se de substituir `feature-grupoX` pelo nome correto do branch do seu grupo.

#### 6. Criar um Pull Request para o Merge com o Branch `main`

Após todos os integrantes do grupo terem feito suas alterações e commits no branch `feature-grupoX`, é hora de combinar (merge) as alterações com o branch `main`.

1. Acesse o repositório no GitHub.
2. Vá até a seção **Pull requests** e clique em **New pull request**.
3. Selecione `feature-grupoX` como o branch de origem e `main` como o branch de destino.
4. Revise as alterações e clique em **Create pull request**.

#### 7. Resolução de Conflitos (se necessário)

Se houver conflitos durante o merge, trabalhem em equipe para resolvê-los. Após resolver, façam um novo commit com a resolução e concluam o pull request.

#### 8. Comentário Final no Pull Request

No pull request, cada integrante deve deixar um comentário breve sobre:
- Um aprendizado ou desafio enfrentado durante a atividade.

---

### Entrega e Avaliação

1. **Entrega**: O pull request deve ser finalizado e aprovado para que as alterações sejam combinadas com o branch `main`.
2. **Avaliação**:
   - **Individual**: Verificação dos arquivos individuais e da participação de cada membro no pull request.
   - **Grupo**: Avaliação da organização do pull request, clareza dos comentários e resolução de conflitos (quando aplicável).

Boa atividade e bom aprendizado sobre Git e controle de versão!
