# pentahoLanguagePacks-fix
Pentaho Language Packs Fix 

Realizamos as correções do processo de ETL do plugin que estava emitindo erro no processamento da instalação dos arquivos de tradução.
A muito tempo foi enviado via PR no git oficial da tradução, que até agora não foi incluido no projeto (https://github.com/webdetails/pentahoLanguagePacks/pull/144) com base na correção descrita criamos este "fix".

# Fix 
- Adicionadas as biblitecas necessárias  para execuçao correta na versão 9x do pentaho
- Atualizado etls do Pull request (Java Heap Overflow)

# Install
- Realizar o Download do release da versão (Exemplo 9x https://github.com/ambientelivre/pentahoLanguagePacks-fix/releases/download/9x/languagePack_pt_BR.zip)
- Descompactar.
- Copiar para o diretório descompactado languagePack_pt_BR para o diretório <pentahoinstall>/pentaho-server/pentaho-solutions/system/
- Reiniciar o Pentaho Server.
- Executar no Pentaho Server no menu Tools -> pentahoLanguagePacks -> Portuguese (Brazilian variant) Language Pack Installer e clique em Install.
- Limpe o cache do Browser (CRTL+F5).

Obs. Se alguns temas ainda não ficaram traduzidos execute o install dio plugin pela segunda vez.

# Versões
https://github.com/ambientelivre/pentahoLanguagePacks-fix/releases
