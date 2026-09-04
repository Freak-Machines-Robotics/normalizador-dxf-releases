# Normalizador DXF

Aplicação da **Freak Robotics** que prepara os ficheiros DXF dos clientes para
serem importados no CypNest sem trabalho manual: limpa o desenho, arruma as
layers, conta as peças repetidas e escreve dentro de cada peça o nome, a
quantidade, o material e a espessura.

É aqui que estão as versões publicadas. **O código-fonte é privado.**

---

## Instalar pela primeira vez

**1. Descarregue o instalador.**

Vá a **[Releases](../../releases/latest)** e, na lista de ficheiros lá em baixo,
descarregue o que tem **`Instalador`** no nome:

> **NormalizadorDXF-Instalador-*(versão)*.zip** ← é este

O outro ficheiro (`NormalizadorDXF-*(versão)*.zip`, sem a palavra *Instalador*)
**não serve** para instalar — é o que a aplicação usa sozinha para se
actualizar. Se descarregar esse por engano, não vai encontrar nada para abrir.

**2. Extraia o ficheiro.**

Clique com o botão direito no `.zip` → **Extrair tudo**. Escolha uma pasta
qualquer; o ambiente de trabalho serve.

Não tente instalar de dentro do `.zip`. Tem mesmo de extrair primeiro.

**3. Abra a pasta extraída e faça duplo clique em `INSTALAR.cmd`.**

Abre-se uma janela preta que copia os ficheiros e cria os atalhos. Quando disser
*"Instalado"*, carregue numa tecla para fechar.

**4. Abra pelo atalho `Normalizador DXF`**, no ambiente de trabalho ou no menu
Iniciar.

Já pode apagar a pasta que extraiu — não faz falta.

### O Windows vai mostrar um aviso

Na primeira vez aparece um ecrã azul a dizer **"O Windows protegeu o seu PC"**
ou *"editor desconhecido"*.

Carregue em **Mais informações** e depois em **Executar assim mesmo**.

Não é sinal de que algo esteja mal. Acontece porque a aplicação não tem
certificado de assinatura de código, e o Windows desconfia de tudo o que não
reconhece. **Só acontece uma vez por computador.**

---

## Usar pela primeira vez

A aplicação funciona **por inteiro durante 30 dias**, sem ser preciso fazer nada.

Passado esse período continua a abrir, a carregar os desenhos e a mostrar tudo —
só **deixa de gravar os ficheiros** até ter licença. Nada do trabalho já feito se
perde.

### Pedir a licença

1. Na aplicação, carregue em **Licença**, no canto superior direito.
2. No topo aparece o **código desta máquina** — cinco grupos de letras e
   números. Carregue em **Copiar**.
3. Envie-o para **geral@freakrobotics.com**, com o nome da empresa e o NIF.

A licença é emitida **para aquele computador**. É isso que permite que funcione
sem ligação à internet.

### Activar

Recebe por email um ficheiro terminado em **`.lic`**. Abra o ecrã **Licença** e
**arraste o ficheiro** para a zona indicada (ou clique nela e escolha-o). A
aplicação confirma na hora.

Guarde o ficheiro: se reinstalar a aplicação no mesmo computador, basta voltar a
carregá-lo.

---

## Actualizações

**Não é preciso voltar a esta página.** A aplicação vê as versões novas sozinha,
transfere-as em segundo plano e mostra uma faixa no topo com o botão
**Reiniciar para actualizar**.

As actualizações são obrigatórias: depois de a versão nova estar transferida, a
aplicação deixa de exportar até ser reiniciada. É um clique, e existe para
garantir que ninguém fica a trabalhar com uma versão que tenha um problema
conhecido. Reinicie quando acabar o lote que tem aberto.

Os perfis de cliente e o histórico de trabalhos **nunca** se perdem numa
actualização.

---

## Requisitos

- **Windows 10 ou 11**, 64 bits
- Ligação à internet apenas para receber actualizações — os desenhos são
  processados no seu computador e **não saem da máquina**
- Nada mais a instalar

---

## Se alguma coisa correr mal

| O que vê | O que fazer |
|---|---|
| O Windows bloqueia a instalação | *Mais informações* → *Executar assim mesmo* |
| Não encontro o `INSTALAR.cmd` | Descarregou o ficheiro sem *Instalador* no nome, ou não extraiu o `.zip` |
| A janela abre no browser em vez de janela própria | Funciona na mesma; avise-nos para vermos porquê |
| Deixou de exportar | Veja o ecrã **Licença**: diz sempre o que falta |

Qualquer dúvida, estamos por aqui.

---

**Freak Robotics** — Vila Nova da Barquinha
geral@freakrobotics.com
