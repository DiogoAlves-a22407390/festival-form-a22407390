# festival

Descreva aqui as alterações/correções que fez

1. Na parte da view for alterado a forma como e que se organiza as datas no html dos dias adicionando um .order_by('data').
2. Esta linha ordering = ["dia__data", "hora"], organiza no html dos dias o dia em que o concerto vai ser e por ordem crescente.
3. Para conseguir alterar mais coisas na parte de editar o concerto foi preciso e ao forms.py e adicionar mais campos uma vez que só tinha o "dia".
4. Tive que criar no ficheiro urls.py um caminho para a função pretendida, apos isso tive que criar a função para apagar o concerto e por fim adicionar o butão ao html
5. Para fazer a parte de criar um concerto tive que fazer a função no views de seguida tive que adiconar o caminho ao urls.py depois fazer o html e por fim adiconar o link ao criar concerto de forma que fosse para outra pagina
6. Adicionar no models o atributo, 
