//No html existe uma tabela com id 'tabela'
//quando o usuário clicar em uma linha da tabela irá redirecionar para outra pagina passando o ID_USU como parametro;
let tabela = document.getElementById('tabela');
//escutador de evento de duplo click
tabela.addEventListener('dblclick', (e) => {
//pega o elemento clicado
  let elementoclicado = e.target;
  let elementopai = elementoclicado.parentNode;
//pega o conteudo da primeira celula
  let conteudocelula = elementopai.cells[0];
//Pega o textContent
  let ID_USU = conteudocelula.textContent;
//redirecionando para uma rota get passando ID_USU como parametro
  location.href = `/visualiza_usuario/${ID_USU}`
})
