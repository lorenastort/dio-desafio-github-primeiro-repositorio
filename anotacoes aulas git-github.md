Este é um passo a passo bem simplificado para após de criado um repositório no Github, conseguir cloná-lo na máquina, inserir novos arquivos e enviá-lo novamente para a nuvem:

1. copiar HTTPS do repositório no Github
2. criar uma pasta onde se deseja colar o aquivo clonado do Github
3. entrar na pasta, clicar com o botão direito do mouse em Git bash here
4. digitar git clone + colar link HTTPS
5. digitar cd + nome da pasta criada (pode se usar tab para completar)
6. digitar git status
7. pode-se criar pastas ou arquivos novos dentro do repositório
8. digitar git status (será identificado que eu criei novos arquivos ou pastas)
9. para enviar ao Github, digitar git add. ou git -a
10. digitar git status (confirmar que o arquivo será considerado no Github)
11. digitar git commit -m " escrever comentario" para criar o commit do arquivo ou pasta que quero enviar
12. digitar git status
13. digitar git push origin main para 'empurar' o aquivo para o  Github  

