# 📢 Projeto Gradio Chatbot
![Gradio](https://pypi-camo.freetls.fastly.net/a95ef5913dc4cc84d2155ff690a0fa0d4c33d7e2/68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f67726164696f2d6170702f67726164696f2f6d61696e2f726561646d655f66696c65732f67726164696f2e737667)

## O que é o Gradio?
[Gradio](https://www.gradio.app/) é uma biblioteca Python que permite criar interfaces de usuário interativas de forma simples e intuitiva. Com poucas linhas de código, é possível construir aplicações web para demonstrar modelos de machine learning, processamento de linguagem natural e outras aplicações sem precisar desenvolver um front-end do zero.

### Principais vantagens do Gradio:
- ✅ Fácil implementação — apenas algumas linhas de código!
- ✅ Compartilhamento rápido via link na nuvem.
- ✅ Integração com TensorFlow, PyTorch, scikit-learn e OpenAI.
- ✅ Perfeito para demonstração de modelos e coleta de feedback de usuários.

---

## Sobre o Projeto
Este projeto utiliza **Gradio** para criar uma interface interativa que permite interagir com um modelo de linguagem da OpenAI. Com essa aplicação, o usuário pode enviar perguntas e receber respostas de forma simplificada, diretamente em um navegador.

### Funcionalidades:
- Interface simples para interação com o modelo GPT-4o-mini.
- Respostas em tempo real utilizando **streaming**.
- Facilidade para testar o modelo sem necessidade de desenvolvimento web.

---

## Tecnologias Utilizadas
Este projeto foi desenvolvido utilizando as seguintes bibliotecas:

```python
# Biblioteca para interagir com o sistema operacional e acessar variáveis de ambiente
import os

# Tipagem para listas, usada para garantir que variáveis sejam listas de tipos específicos
from typing import List

# Biblioteca para carregar variáveis de ambiente a partir de arquivos .env
from dotenv import load_dotenv

# Biblioteca para interação com a API da OpenAI, incluindo geração de textos com GPT
from openai import OpenAI

# Gradio é usado para criar interfaces de usuário interativas de forma simples e rápida
import gradio as gr
```

---


## 📌 Documentação do Gradio
Para saber mais sobre as funcionalidades do Gradio, acesse a [documentação oficial](https://www.gradio.app/).


Se este projeto te ajudou, não esqueça de dar uma ⭐ no repositório e compartilhar! 🚀

