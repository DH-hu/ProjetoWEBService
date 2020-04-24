# ProjetoWEBService
Exercício da matéria da disciplina de Frameworks de Desenvolvimento Web.

🚀 Tecnologias usadas
Esse projeto foi desenvolvido com as seguintes tecnologias:

Eclipse
Java jre 8
💻 Comandos
Primeiro execute, para criar os arquivos WSDL e XSD.

$ wsgen -cp bin -s src -wsdl controle.Echo

Depois execute esse comando para criar o pacote cliente.

$ wsimport -s src -d bin -p cliente http://localhost:10000/echo?wsdl

♻️ Como contribuir
Fork esse repositório;
Crie uma branch com a sua feature: git checkout -b my-feature
Commit suas mudanças: git commit -m 'feat: My new feature'
Push a sua branch: git push origin my-feature
Depois que o merge da sua pull request for feito, você pode deletar a sua branch.

🎓 Quem ministrou?
A aula foi ministrada pelo Thiago Souza

📝 Licença
Esse projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
