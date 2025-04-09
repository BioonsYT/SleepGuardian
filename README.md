![Versão](https://img.shields.io/badge/vers%C3%A3o-v2.0-green)

# 🛡️ Sleep Guardian v2 — by Bioons
![banner do titulo](https://github.com/user-attachments/assets/ce3d9970-05e4-42e6-bbbe-32e2529a4706)
### 🧠 O que é?

**Sleep Guardian** é uma ferramenta leve e inteligente que roda em segundo plano e coloca seu computador automaticamente em modo de **suspensão**, **baseado em inatividade real de teclado e mouse**.

Ao contrário da função nativa do Windows, que pode ser interrompida por programas abertos ou focados, o **Sleep Guardian ignora esses fatores** e foca apenas na sua interação com o sistema — **teclado e mouse**.

> ✅ Ideal para quem deixa o PC ligado sem perceber e quer **economizar energia** de forma prática.

---

## ⚙️ Funcionalidades da v2

✅ Suspende o PC após tempo ajustável de inatividade (1 a 60 minutos)  
✅ Interface visual intuitiva com abas de informações e logs  
✅ Monitora uso de teclado e mouse com inteligência — ignora micro-movimentos  
✅ Permite definir um **processo-chave** (ex: `umjogo.exe`, `Blender.exe`) que **bloqueia a suspensão** enquanto estiver aberto e em foco  
✅ Inicia monitoramento automaticamente ao abrir  
✅ Ícone embutido no `.exe` (sem necessidade de arquivos externos)  
✅ Permite restaurar a janela com clique duplo no ícone da bandeja  
✅ Opção de sair com clique direito no menu da bandeja  
✅ Notificação “Rodando em segundo plano” ao ser minimizado  
✅ Informações de bateria e uptime em tempo real  
✅ Logs com registros dos eventos e contagem regressiva antes da suspensão  
✅ Aviso sonoro 10 segundos antes de suspender  
✅ Prevenção de múltiplas instâncias (evita abrir mais de um Sleep Guardian ao mesmo tempo)

---

## 🔑 Sobre a função de chave

Você pode definir um **processo-chave** que serve como "bloqueador" da suspensão.  
Por padrão, usamos a **Calculadora do Windows** (`CalculatorApp.exe`).

**Como funciona:**

- Se o app-chave **estiver em primeiro plano e ativo**, o monitoramento é pausado
- Se o app estiver aberto mas **não estiver em foco**, ele **não bloqueia**
- Se o app **não estiver rodando**, o Sleep Guardian ativa a contagem e suspende o sistema após o tempo definido

> 💡 Você pode trocar a chave digitando o nome de outro processo na interface, sem precisar reiniciar.

---

## 🖥️ Interface

Veja abaixo como é a interface do **Sleep Guardian v2**:

### 🟢 Interface Inicial
![Interface inicial](preview%20-%20sleep%20interface%20inicial.png)

### 🟡 Interface de Logs
![Interface de logs](preview%20-%20sleep%20interface%20de%20logs.png)

### 🔵 Ícone na Bandeja
![App na bandeja](preview%20-%20sleep%20na%20bandeja.png)

### 🟣 Menu ao clicar com botão direito
![Botões de sair e restaurar](preview%20-%20sleep%20botoes%20de%20sair%20e%20restaurar.png)

---

## 🛣️ Histórico do projeto

| Versão | Mudanças                                                                                   | Status        |
|--------|---------------------------------------------------------------------------------------------|---------------|
| v1     | Suspende após 30 min, ícone na bandeja, usa Calculadora como chave                          | ✅ Concluída   |
| v2     | Interface, processo-chave editável, ícone embutido, logs visuais, melhorias no monitoramento | 🟢 Atual       |
| v3     | Nova lógica de suspensão, múltiplas chaves ou métodos inteligentes                          | 🔜 Em planejamento |

---

## 📥 Como usar

1. Baixe o `.zip` na aba [Releases (Download da V2 aqui)](https://github.com/BioonsYT/SleepGuardian/releases/tag/v2.0)
2. Extraia os arquivos para uma pasta
3. Abra o `SleepGuardian_v2.exe`
4. O ícone aparecerá na bandeja e o monitoramento será iniciado
5. Ajuste o tempo de inatividade (1 a 60 minutos)
6. (Opcional) Digite o nome de um processo-chave para impedir a suspensão
7. Minimize se quiser — ele continuará ativo em segundo plano

---

## 💡 Dica

Para economizar energia, configure o tempo para 5 ou 10 minutos.  
Mesmo que você esqueça o PC ligado, o Sleep Guardian vai agir por você.  
🟢 Ideal para quem deixa música, IDEs ou tarefas abertas.

---

## 🧾 Sobre a versão 1

Você ainda pode baixar e usar a versão anterior:

### 🔹 Sleep Guardian v1 — clássico e funcional
- ✅ Suspende o PC após 30 minutos de inatividade
- 🔐 Usa a Calculadora como chave
- 📦 Arquivo `.ico` externo é necessário
- 🔧 Sem interface — roda apenas na bandeja

🔗 [Baixar Sleep Guardian v1](https://github.com/BioonsYT/SleepGuardian/releases/tag/v1.0)

---

## 💻 Requisitos e Compatibilidade

> ✅ Funciona em qualquer computador com **Windows 10 ou superior**  
> ❌ Não é compatível com macOS ou Linux  
> 🔒 Seguro e leve — não requer instalação

---

## 🧑‍💻 Desenvolvedor

Desenvolvido por [Bioons](https://github.com/BioonsYT)  
Versão atual: `v2.0`  
Licença: **Gratuito para uso pessoal**

---

## ❤️ Agradecimentos

Criado com 💻, ☕ e muita insistência pra não deixar o PC ligado à toa.  
Se você curtiu o projeto, deixe uma ⭐ no repositório e compartilhe com seus amigos.

![banner rodape](https://github.com/user-attachments/assets/cc476adc-aa1d-4061-8d85-87ed4e6753df)
