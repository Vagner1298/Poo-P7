class Fila {
    
    Pessoas : string [ ]  =  [ ]
    maxQueue  =  5
    fim  =  0
    nprimeiro  =  0
    nItens  =  0

   
    isEmpty ( ) : número {
        if ( this . nItems  ==  0 ) {
            retornar  1
        } senão {
            retornar  0
        }
    }
    
    isFull ( ) : número {
        if ( this . fim  ==  this . maxQueue ) {
            retornar  1
        } senão {
            retornar  0
        }
    }

   
    addQueue ( nome : string ) : void {
        if ( this . isFull ( )  ==  1 ) {
            consola . log ( 'Fila está cheia!' )
        } senão {
            isso . Gente [ isso . fim ]  =  nome
            consola . log ( nome + 'entrou na fila' )
            isso . fim ++
            isso . nItens ++
        }
    }
   
    removeQueue ( ) : string  |  vazio  {
        if ( this . isEmpty ( )  ==  1 ) {
            consola . log ( 'A fila está vazia!' )
        } senão {
            deixe  temp  =  this . Gente [ isso . nprimeiro ]
            consola . log ( this . People [ this . nprimeiro ] + 'saiu da fila' )
            isso . nprimeiro ++
            isso . nItens --
             temperatura de retorno
        }
    }
    
    viewQueue ( ) : void {
        if ( this . isEmpty ( )  ==  1 ) {
            consola . log ( 'Fila não tem ninguém!' )
        } senão {
            seja  np  =  isso . nprimeiro
            for ( deixe  i = 0 ;  i  <  this . nItems ;  i ++ ) {
                consola . log ( this . People [ np ] + 'está na fila' )
                np ++
            }
        }
    }
}

let  fila : Queue  =  new  Queue ( )


fila . addQueue ( 'Arlindo' )
fila . addQueue ( 'Miguel' )
fila . addQueue ( 'Pedro' )
fila . addQueue ( 'Fernanda' )
consola . log ( '-------------------------' )

fila . removeQueue ( )
fila . removeQueue ( )
fila . removeQueue ( )
consola . log ( '-------------------------' )

fila . addQueue ( 'Larissa' )
consola . log ( '-------------------------' )

fila . verFila ( )
consola . log ( '-------------------------' )

fila . removeQueue ( )
fila . removeQueue ( )
consola . log ( '-------------------------' )

fila . verFila ( )
