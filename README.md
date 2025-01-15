# Projeto: Reconhecimento de Letras em LIBRAS

Este é um projeto de machine learning que reconhece letras do alfabeto de LIBRAS (Língua Brasileira de Sinais) feitas com as mãos. O modelo é capaz de deduzir a letra correspondente ao movimento manual capturado, exibindo-a na tela.

⚠ **Atenção:** O modelo não é perfeito. Ele pode interpretar qualquer movimento das mãos como uma letra do alfabeto de LIBRAS, mesmo que não corresponda a uma letra real. Contudo, ao fazer um gesto correto de uma letra de LIBRAS, o modelo tem boa precisão em identificá-la.

---

## 🚀 Funcionalidades
- Reconhece e exibe a letra correspondente de LIBRAS a partir de gestos feitos com as mãos.
- Utiliza um modelo de machine learning treinado para detecção de padrões manuais.
- Feedback visual em tempo real.

---

## 🛠️ Tecnologias Utilizadas
- **Python**: Linguagem de programação principal.
- **OpenCV**: Para captura e processamento de imagens.
- **TensorFlow/Keras**: Framework para treinamento e inferência do modelo de machine learning.

---

## 📦 Como Usar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Execute o script principal**:
   ```bash
   python main.py
   ```

4. **Faça os gestos**:
   - Posicione sua mão na frente da câmera.
   - Faça um gesto de uma das primeiras quatro letras do alfabeto de LIBRAS.
   - A letra correspondente será exibida na tela.

---

## 🤔 Limitações
- O modelo pode interpretar qualquer movimento manual como uma letra, mesmo que o gesto não seja uma letra de LIBRAS.
- Luz ambiente, qualidade da câmera e outros fatores podem influenciar na precisão do reconhecimento.

---

## 🛠️ Melhorias Futuras
- Ajustar o modelo para diferenciar entre gestos válidos e não válidos.
- Melhorar a robustez em ambientes com diferentes condições de iluminação.
- Expandir para reconhecimento de palavras e frases completas em LIBRAS.

---

## 📄 Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma [issue](https://github.com/andreasgrum00/libras_recognizer/issues) ou enviar um [pull request](https://github.com/andreasgrum00/libras_recognizer/pulls).

1. Faça um fork do projeto.
2. Crie uma branch para sua feature ou correção:
   ```bash
   git checkout -b minha-feature
   ```
3. Envie suas alterações:
   ```bash
   git push origin minha-feature
   ```
4. Abra um pull request.

---

## 💬 Contato
Se você tiver dúvidas ou sugestões, entre em contato:
- Email: andreasgrum00@gmail.com
