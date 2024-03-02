# Email-Similarity
Script que utiliza o modelo Naive Bayes para avaliar a similaridade de Emails em dataset definido pela codecademy (poderá ser utilizado qualquer dataset de preferencia)

neste modelo, podera ser testado com varios sets:
'alt.atheism'
'comp.graphics'
'comp.os.ms-windows.misc'
'comp.sys.ibm.pc.hardware'
'comp.sys.mac.hardware'
'comp.windows.x'
'misc.forsale'
'rec.autos'
'rec.motorcycles'
'rec.sport.baseball'
'rec.sport.hockey'
'sci.crypt'
'sci.electronics'
'sci.med'
'sci.space'
'soc.religion.christian'
'talk.politics.guns'
'talk.politics.mideast'
'talk.politics.misc'
'talk.religion.misc'


Somente modifique as proximas duas linhas de codigo, adicionando as listas de preferencia para os testes:


train_emails = fetch_20newsgroups(categories = ['comp.sys.ibm.pc.hardware', 'rec.sport.hockey'], subset = 'train', shuffle = True, random_state = 108)
test_emails = fetch_20newsgroups(categories = ['comp.sys.ibm.pc.hardware', 'rec.sport.hockey'], subset = 'test', shuffle = True, random_state = 108)

Divirta-se :)
