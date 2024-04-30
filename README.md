Este script se generó con el fin de pasar desde archivos abIF obtenidos de la secuenciacion de ADN por sanger a una secuencia final consenso por primer. 
Por tanto, lo que consigue este es pasar de abIF a fastQ, y de fastQ hace alineamiento por pares entre forward y reverse obteniendo la consenso. 

El scrips genera dos output: 
  - consensuses: son todas las consensos generadas.
  - resultados_fasta: dos archivos:
                  (1) consenso, y
                  (2) aln: alineamiento entre forward, reverse y ademas añadida la consenso. esto es puro ahorro para ruth. 
