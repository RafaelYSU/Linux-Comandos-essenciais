# Wiki de comandos Linux

Trarei os detalhes do que classificaria como "Essencial" dos comando do Linux para laboratórios, tendo como base o guia Foca GNU/Linux, de modo a trazer eficiência será separada por categorias


**Navegação e Organização**


## pwd 
**Função:** Mostra o caminho do diretório atual
**Exemplo**
```bash
pwd
```

## ls 
**Função:** Lista os arquivos de um diretório
**Exemplo**
```bash
ls -lh
```

## cd
**Função:** Entra em um diretório
**Exemplo**
```bash
cd [diretório]
```

## mkdir
**Função:** Cria um diretório no sistema
**Exemplo**
```bash
mkdir [opções] [caminho/diretório] [caminho1/diretório1]
```

## rmdir
**Função:**  Remove um diretório vazio do sistema 
**Exemplo**
```bash
rmdir [caminho/diretório] [caminho1/diretório1]
```


**Manipulação de arquivos**


## cat
**Função:** Mostra o conteudo de arquivo de texto
**Exemplo**
```bash
cat [opções] [diretório/arquivo] [diretório1/arquivo1]
```

## tac
**Função:** Mostra o conteudo de arquivo de texto porém em ordem inversa
**Exemplo**
```bash
tac [opções] [diretório/arquivo] [diretório1/arquivo1]
```

## rm
**Função:** Apaga arquivos 
**Exemplo**
```bash
rm [opções][caminho][arquivo/diretório] [caminho1][arquivo1/diretório1]
```

## cp
**Função:** Copia arquivos
**Exemplo**
```bash
cp [opções] [origem] [destino]
```

## mv
**Função:** Move ou renomeia arquivos
**Exemplo**
```bash
mv [opções] [origem] [destino]
```


**Processamento e Filtros**


## grep
**Função:** Busca padrões ou sequências específicas em arquivos
**Exemplo**
```bash
grep [expressão] [arquivo] [opções]
```

## head
**Função:** Mostra as linhas iniciais de um arquivo texto
**Exemplo**
```bash
head [opções]
```

## tail
**Função:** Mostra as linhas finais de um arquivo de texto
**Exemplo**
```bash
tail [opções]
```

## wc
**Função:** Conta o número de palavras, bytes e linhas em um arquivo ou entrada padrão
**Exemplo**
```bash
wc [opções] [arquivo]
```

## sort
**Função:** Organiza as linhas de um arquivo texto ou da entrada padrão
**Exemplo**
```bash
sort [opções] [arquivo]
```

## cut
**Função:** Mostra seções de cada linha do arquivo dependendo das opções passadas ao programa
**Exemplo**
```bash
cut [opções] [arquivo]
```

## diff
**Função:** Compara dois arquivos e mostra as diferenças entre eles
**Exemplo**
```bash
diff [diretório1/arquivo1] [diretório2/arquivo2] [opções]
```

## less
**Função:** Permite fazer a paginação de arquivos ou da entrada padrão
**Exemplo**
```bash
less [arquivo]
```

## more
**Função:** Similar ao less, mas leitura simples
**Exemplo**
```bash
more [arquivo]
```

## find
**Função:** Procura por arquivos/diretórios no disco
**Exemplo**
```bash
find [diretório] [opções/expressão]
```


**Monitoramento do sistema**


## ps
**Função:** Lista os processos ativos no sistema
**Exemplo**
```bash
ps [opções]
```

## top
**Função:** Monitora o uso de CPU e RAM em tempo real
**Exemplo**
```bash
top [opções]
```

## kill
**Função:** Interrompe um processo travado
**Exemplo**
```bash
kill [opções] [sinal] [número]
```

## free
**Função:** Mostra detalhes sobre a utilização da memória RAM do sistema
**Exemplo**
```bash
free [opções]
```

## df
**Função:** Mostra o espaço livre/ocupado de cada partição
**Exemplo**
```bash
df [opções]
```

## du
**Função:** Mostra o espaço ocupado por arquivos e sub-diretórios do diretório atual
**Exemplo**
```bash
du [opções]
```

## uptime
**Função:** Mostra o tempo de execução do sistema desde que o computador foi ligado
**Exemplo**
```bash
uptime
```


**Permissões e auxilios**


## chmod
**Função:** Muda a permissão de acesso a um arquivo ou diretório
**Exemplo**
```bash
chmod [opções] [permissões] [diretório/arquivo]
```

## man
**Função:** Abre o manual de ajuda de qualquer comando
**Exemplo**
```bash
man [seção] [comando/arquivo]
```

## clear
**Função:** Limpa a tela e posiciona o cursor no canto superior esquerdo do vídeo
**Exemplo**
```bash
clear
```
