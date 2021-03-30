# pentahoLanguagePacks-fix
Pentaho Language Packs Fix 

Realizamos as correções do processo de ETL do plugin que estava emitindo erro no processamento da instalação dos arquivos de tradução.
A muito tempo foi enviado via PR no git oficial da tradução e até agora não foi incluido no projeto (https://github.com/webdetails/pentahoLanguagePacks/pull/144) com base na correção descrita criamos os ajustes.

# fix 
- Adicionadas as biblitecas necessárias  para execuçao correta na versão 9x do pentaho
- Atualizado etls do Pull request (Java Heap Overflow)

# Install
- Realizar o Download do release da sua versão ( Exemplo 9x )
- Descompactar
- Copiar para o diretório languagePack_pt_BR para o diretório <pentahoinstall>/pentaho-server/pentaho-solutions/system/
- Reiniciar o Pentaho Server.
- Executar no Pentaho Server no meno Tools -> pentahoLanguagePacks -> Portuguese (Brazilian variant) Language Pack Installer e clique em Install.
- Limpe o cache do Browser (CRTL+F5).
