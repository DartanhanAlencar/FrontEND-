
## Descrição dos Diretórios e Arquivos

### **📁 data**
- Contém arquivos ou informações auxiliares ao projeto, como mocks, arquivos de configuração ou qualquer outro tipo de dado estático utilizado internamente.

### **📁 public**
- Contém os arquivos estáticos que não passam pelo processamento do bundler. Esses arquivos ficam acessíveis diretamente no servidor final.


### **📁 src**
- Contém o código-fonte principal da aplicação.
  - **Componentes:** Componentes reutilizáveis do frontend.
  - **Estilos:** Arquivos CSS ou SCSS para estilização.
  - **Utilitários:** Funções auxiliares ou hooks personalizados.
  - **Páginas:** Estrutura principal para navegação e organização do conteúdo.

### **eslint.config.js**
- Arquivo de configuração do ESLint, usado para definir regras e padrões de codificação no projeto.

### **index.html**
- O arquivo inicial da aplicação. 
  - Serve como o ponto de entrada da aplicação no navegador.
  - Contém a inclusão do arquivo JavaScript gerado pelo bundler.

### **package.json**
- Gerencia as dependências e scripts do projeto.
  - Inclui informações sobre as bibliotecas utilizadas, como React e Axios.
  

### **package-lock.json**
- Gerencia as versões exatas das dependências instaladas para garantir consistência ao instalar o projeto em diferentes ambientes.

### **vite.config.js**
- Arquivo de configuração do Vite, responsável por configurar o comportamento do bundler.
  - Inclui definições como aliases, plugins, ou variáveis de ambiente.

