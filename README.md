# Photo Editor version one
Projeto das disciplinas de Práticas de técnicas de programação e Introdução às tecnicas de Programação
####Professora:
Marjory Abreu
####Aluno: 
Adelino Afonso Fernandes Avelino
####Programa: 
Editor de Imagens via terminal 
####Linguagem: 
C
####Funções:
Binarização da imagem usando thresholding    
Filtro grayscale(Tons de cinza)              
Filtro que inverte as cores da imagem         
Faz um espelhamento da imagem                
Rotaciona a imagem                            
Deixar a imagem em alto relevo                
Ampliar imagem                              
Reduzir imagem                              
Sharpering 'Passa-Alta'                       
Blurring 'Passa-Baixa'                        
Filtro Gaussiano                            
Filtro laplace                               
###Como compilar e executar:
É bem simples, abra seu terminal no diretório que está o programa e digite sh compilador.sh
#### BUG:
Está havendo um estouro de pilha na alocação de imagens maiores que 2048 x 2048. Quando a pilha de chamada usa mais memória do que suporta, ocorre um estouro. Mas irei resolver isto futuramente usando alocação dinâmica... Use estas imagens disponíveis para teste.
