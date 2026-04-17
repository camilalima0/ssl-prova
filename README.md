Camila Claudino de Lima
Ambiente Debian - Virtual Box
IP 10.0.2.15

**Dificuldades**
Durante a execução da atividade, os principais desafios foram:

Versionamento (Git): Erro no primeiro push, resolvido ao compreender que a branch main só é reconhecida pelo repositório remoto após a criação do primeiro commit local.

Usuários e SCP: Confusão inicial entre a máscara visual do terminal (PS1 com o meu nome) e o usuário real do sistema (root). Isso gerou falhas de autenticação no comando scp, resolvidas ajustando a sintaxe e redefinindo a senha do root para testar no localhost.

Servidor Python: Entender que o módulo http.server sobe nativamente apenas em HTTP (texto claro). Como ele não carrega os certificados gerados automaticamente, a tentativa de acesso via HTTPS gerou o erro de protocolo esperado no navegador.

**Conclusão**
A realização desta atividade foi fundamental para consolidar conceitos teóricos de Segurança de Sistemas na prática. Através da utilização do OpenSSL, foi possível compreender o fluxo completo da Infraestrutura de Chaves Públicas (PKI), desde a geração de uma chave privada RSA até à criação de uma Requisição de Assinatura de Certificado (CSR) e a posterior auto-assinatura do certificado (Self-Signed).

A experiência permitiu distinguir claramente o papel da criptografia assimétrica na proteção de dados em trânsito e a importância das Autoridades Certificadoras (CA) na cadeia de confiança da internet. Além disso, a prática reforçou competências em administração de sistemas Linux e versionamento de código, competências essenciais para o desenvolvimento de aplicações seguras e para a gestão de infraestruturas tecnológicas modernas.