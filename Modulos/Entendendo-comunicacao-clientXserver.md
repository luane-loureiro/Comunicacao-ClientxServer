# Comunicacao Client X Server
## Aula 1 - História da Web
- A história da internet começa no ambiente da Guerra Fria (1945-1991). As duas super potências envolvidas, Estados Unidos e União Soviética, estavam divididas nos blocos socialista e capitalista e disputavam poderes e hegemonias.
- Com o intuito de facilitar a troca de informações, pois temiam ataques dos soviéticos, o Departamento de Defesa dos Estados Unidos (ARPA - Advanced Research Projects Agency) criou um sistema de compartilhamento de informações entre pessoas distantes geograficamente, a fim de facilitar as estratégias de guerra.
- Nesse momento, surge o protótipo da primeira rede de internet, a Arpanet (Advanced Research Projects Agency Network).
- Assim, no dia 29 de outubro de 1969 foi estabelecida a primeira conexão entre a Universidade da Califórnia e o Instituto de Pesquisa de Stanford. Foi um momento histórico, uma vez que o primeiro e-mail foi enviado.

### Grandes Nomes 
#### Grace Murray Hopper
 - Marinha dos EUA
 - Uma das primeiras programadoras do Mark I em 1944
 - Criadora da linguagem de programação de alto nível flow-Matic (base do COBOL)
 - Termo "bug" na computação

#### Joseph Carl Robnet licklider
- Recrutado pela DARPA depois de teorizar sobre uma rede "galática" de computadores.
- "Plantou a semente" da comunicação entre dois pontos distintos atravez do computador.

#### Robert E. Kahn
- Primeira apresentação pública da ARPANet
- Apresentou o Primeiro e-mail
- criador do TCP/IP
  
#### Tim Berners-Lee
- Inventor do WWW
- Diretor do W3C, world wide web consortion
- Diversas homenagens, incluido o título de cavaleiro dado pela Rainha Elizabeth
- Popularizou o HTTP e HTML.

#### Makc Andersen
- (re)inventou o navegador. o Netscape navigator feito a partir do mosaic.
- Tornou o navegaador "amigavel, com recursos  gráficos
- Deteve 90% da internet na época, mas sendo superado pelo internet explorer anos mais tarde.

#### Bill Gates
- Fundador da Microsoft.
- Equipe microsoft criou o Internet Explorer
- Tornou acessivél para todos os computadores, e com isso o acesso a internet.  

#### Steve Jobs
- Fundador da Apple
- Cocorrente direta da Microsoft
- Popularizou o Smartphone como conhecemos hoje, atravéz do lansamento do iphone em 29 de junho de 2007.

  ## Aula 2 - O que são clientes?
- cliente é quem consome a informação.

[![](https://mermaid.ink/img/pako:eNqrVkrOT0lVslJSSC9KLMhQ8AmKyVMAAsfoD_Mn7VZIzslMzSspjlWw0dW1U3DR0Pgwv2eCgmdeSWpRXmqJpiZEsRNQ8bSl73f0E6ceoglTEqQJqMsVaFr_GoXg1KKy1KJYqA4opaSjlJtalJuYmQJ0cjVIMEapJCM1NzVGyQrITElNSyzNKYlRismrBSpNLC3JD67MS1ayKikqTdVRKi1ISSxJdclMBPo1V8kqLTGnGCiampJZkl_kCwkGcGjUAgDF7GAD?type=png)](https://mermaid.live/edit#pako:eNqrVkrOT0lVslJSSC9KLMhQ8AmKyVMAAsfoD_Mn7VZIzslMzSspjlWw0dW1U3DR0Pgwv2eCgmdeSWpRXmqJpiZEsRNQ8bSl73f0E6ceoglTEqQJqMsVaFr_GoXg1KKy1KJYqA4opaSjlJtalJuYmQJ0cjVIMEapJCM1NzVGyQrITElNSyzNKYlRismrBSpNLC3JD67MS1ayKikqTdVRKi1ISSxJdclMBPo1V8kqLTGnGCiampJZkl_kCwkGcGjUAgDF7GAD)

- o cliente solicita a informação ao servidor, e ele retorna o arquivo.
- Esses arquivos podem ser dinamico ou estáticos.
- Conteudos estaticos são enviados diretamente do servidor para o cliente.
- quando o servidor envia os arquivos os navegadores crian arquivos cash, q sao utilizados pra carregar o site mais rapidamnte da proxima vez que o cliente tentar acessar o site.

### Sites Estáticos:
Um site estático é composto de páginas da web criadas usando HTML, CSS e Javascript 
Cada página de um site estático é armazenada como um único arquivo HTML, que é entregue do servidor diretamente para a página da web da forma como está. Esse conteúdo se torna parte do design da sua página e não mudará a menos que o arquivo HTML original seja editado usando código.


#### Vantagens de um site Estático:
- Velocidade mais rápida de carregamento da página
- Criação rápida
- Segurança potencialmente maior

#### Desvantágens de um site Estático:
- Escalabilidade limitada
- Gestão menos eficiente

### Sites Dinâmicos
São criados utilizando linguagem e tecnologia do lado do servidor, os sites dinâmicos permitem que o conteúdo de cada página seja entregue e exibido dinamicamente
Os Sites dinâmicos oferecem a possibilidade de personalizar o conteúdo do site para um usuário específico. Eles também permitem que você faça alterações em várias páginas ao mesmo tempo, pois as modificações feitas em uma página dinâmica podem ser automaticamente aplicadas a milhares.

#### Vantagens de um site Dinâmico:
- Atualização fácil
- Melhor experiência do usuário
- Mais funcionalidades
  
#### Desvantágens de um site Estático:
- Necessidade de mais recursos para a criação
- Problemas de desempenho

### Design Despomsivo e Responsabilidade
- um site responsivo deve se adaptar de forma legivel em qualquer dispositivo.
- Também deve ser compativel com diferentes tipos de navegadores.
  
### Navegadores
- são programas criados por empresas, utizados para abrir/executar arquivos.
- Seguem padrões W3S, porem, sempre tem uma diferença ou outra interpretação.
- também são chamados de "browsers"
- Iniciou com o MOSAIC, passou para netscape e hoje temos uma variedade de navegadores disponíveis.
- Gratuítos.

### Aplicações Web
são soluções criadas que possuem a internet como meio de municação entre cliente x server não sendo necessaria sua instalação.

[![](https://mermaid.ink/img/pako:eNqNkLFqAkEQhl9lmEpBX-AQIXJJCMRGy9srhtsxLtztyroXCOIbBAwG0l4Ve7uA4CvlHsExaxUbp5nh_7-fgX-FhdOMCcKLp8UcnifKgsxd1jbbAxSlYRs4h0G_P4S002mb9w94EslbDt1uhEcCf33__mxu5B-F_9zfBsfEtRlD99mU_avRzkPbbHZ5pP-rkX3IRmQLB5ohJe2W4m2P-eXJZWEPK_YVGS2VrM6iwjDnihUmcmqeUV0GhcquBaU6uOmbLTAJvuYe1gtNgVND0mWFyYzKpaisTXB-HGv-a3t9AuF_gxo?type=png)](https://mermaid.live/edit#pako:eNqNkLFqAkEQhl9lmEpBX-AQIXJJCMRGy9srhtsxLtztyroXCOIbBAwG0l4Ve7uA4CvlHsExaxUbp5nh_7-fgX-FhdOMCcKLp8UcnifKgsxd1jbbAxSlYRs4h0G_P4S002mb9w94EslbDt1uhEcCf33__mxu5B-F_9zfBsfEtRlD99mU_avRzkPbbHZ5pP-rkX3IRmQLB5ohJe2W4m2P-eXJZWEPK_YVGS2VrM6iwjDnihUmcmqeUV0GhcquBaU6uOmbLTAJvuYe1gtNgVND0mWFyYzKpaisTXB-HGv-a3t9AuF_gxo)

### Dispositivos móveis
- laptop, tablets, celulares, ipads, samert watch, videogames...
- A internt já não é o futuro, ja estamos vivendo ele.
- a internet est'presente em nossas vidade, e majoritáriamente através dos dispositivos móveis.

## Aula 3 - O que são servidores?
### Sobre servidores
- São computadores q oferecem os arquivos para serem consumidos.

[![](https://mermaid.ink/img/pako:eNqrVkrOT0lVslJSSC9KLMhQ8AmKyVMAAsfoD_Mn7VZIzslMzStJjVWw0dW1U3DR0Pgwf3rL-x39Cj6JeQq6CsWpRWWZKflFCjn5yYk5mpoQvU5AvdOWglSRpd0dqH3yRrL0QgwgqBZipCvQnunNIFXBMPlYhCkxeVBKSUcpN7UoNzEzBRhK1SDBGKWSjNTc1BglKyAzJTUtsTSnJEYpJq8WqDSxtCQ_uDIvWcmqpKg0VUeptCAlsSTVJTMRGLy5SlZpiTnFQNHUlMyS_CJfSMiDI6AWAOE_jFI?type=png)](https://mermaid.live/edit#pako:eNqrVkrOT0lVslJSSC9KLMhQ8AmKyVMAAsfoD_Mn7VZIzslMzStJjVWw0dW1U3DR0Pgwf3rL-x39Cj6JeQq6CsWpRWWZKflFCjn5yYk5mpoQvU5AvdOWglSRpd0dqH3yRrL0QgwgqBZipCvQnunNIFXBMPlYhCkxeVBKSUcpN7UoNzEzBRhK1SDBGKWSjNTc1BglKyAzJTUtsTSnJEYpJq8WqDSxtCQ_uDIvWcmqpKg0VUeptCAlsSTVJTMRGLy5SlZpiTnFQNHUlMyS_CJfSMiDI6AWAOE_jFI)

- Rede local são vários computadores que se ligam entre sí e tem um computador central como apoio.
  
[![](https://mermaid.ink/img/pako:eNqVkcFKAzEQhl9lmFMXui-wFKFuVYQKRcWL6WHYTG0gm4Q0EaT05lFQFPTYkw_gTfSh7COYdXuwve1cMvz83z-Qf4mVlYwFwo0nN4fxuTCQZni9WT9_gyYXrJvCIM8PYNTrbdZv9z-fjzAmAzks2N8qaT1oW5HOshY9TOjre-OalN3Ik0S-fEDJOmry3djjhv2Cy6tOWMv-805KkAxDZ5XNMmiCjlLwwxOcmsDecJi2yL4Kezd3crantg_2sWZfk5Lp25eNKDDMuWaBRVolzyjqIFCYVbJSDPbizlRYBB-5j9FJCjxSlPqqsZiRXiSVpQrWn7VV_jW6-gU2Nqj7?type=png)](https://mermaid.live/edit#pako:eNqVkcFKAzEQhl9lmFMXui-wFKFuVYQKRcWL6WHYTG0gm4Q0EaT05lFQFPTYkw_gTfSh7COYdXuwve1cMvz83z-Qf4mVlYwFwo0nN4fxuTCQZni9WT9_gyYXrJvCIM8PYNTrbdZv9z-fjzAmAzks2N8qaT1oW5HOshY9TOjre-OalN3Ik0S-fEDJOmry3djjhv2Cy6tOWMv-805KkAxDZ5XNMmiCjlLwwxOcmsDecJi2yL4Kezd3crantg_2sWZfk5Lp25eNKDDMuWaBRVolzyjqIFCYVbJSDPbizlRYBB-5j9FJCjxSlPqqsZiRXiSVpQrWn7VV_jW6-gU2Nqj7)

#### Tipos de servidores 
- Arquivos
- Segurança (firewall)
- Streaming
- E-mail
- Web
  
### Conceito de Servers
#### Softwares
- Sistemas operacionais
- Monitoramento
- servidores web

#### Hardware
- Armazenamento
- Memória
- Processadores

#### Sistemas opreacionais
- Windows server
- Ubuntu
- CentOS
- Debian
- Fedora
- Oracle

#### Servidores Web
- Apache
- Nginx
  
[![](https://mermaid.ink/img/pako:eNplkLFqAzEMhl9FaGrA9wI3FEIypCWBEt9WZxBnJTGc7avPDikhW_dCl44ZOvQVCh3zQM0j1JdAIVSLxC_x8evfYe01Y4mwCtSuYTpXDnINH0-Ht28YNYZd5AUUBcz5KZnOHD-PHx5gUlUPWb2F8c3p8P7y8_UKksPGaB8GF8T_BQx6zqSaTQWMpBRwTxuSdTBtFHBnacWuE1DxNvqiR1-ZWCh35v41FGg5WDI629_1osK4ZssKyzxqXlJqokLl9vmUUvTy2dVYxpBYYGo1RR4byn9bLJfUdFllbaIPs0sk52T2v2gmZVM?type=png)](https://mermaid.live/edit#pako:eNplkLFqAzEMhl9FaGrA9wI3FEIypCWBEt9WZxBnJTGc7avPDikhW_dCl44ZOvQVCh3zQM0j1JdAIVSLxC_x8evfYe01Y4mwCtSuYTpXDnINH0-Ht28YNYZd5AUUBcz5KZnOHD-PHx5gUlUPWb2F8c3p8P7y8_UKksPGaB8GF8T_BQx6zqSaTQWMpBRwTxuSdTBtFHBnacWuE1DxNvqiR1-ZWCh35v41FGg5WDI629_1osK4ZssKyzxqXlJqokLl9vmUUvTy2dVYxpBYYGo1RR4byn9bLJfUdFllbaIPs0sk52T2v2gmZVM)

### Tipos de Servidores
#### Conceito de servers
- Arquivos
- Seguranças (firewall)
- Streaming
- E-Mail
- Web

#### Proxy
[![](https://mermaid.ink/img/pako:eNqFkbFKA0EQhl9lmCqB3AscIuhFRVAQIzZuiiU7MQd7u8c6K4aQzlJQFLRM5QPYiT5U8gjO5Q4Lj8Sphm8-fgb-GY68IUwRroMuJ3ByrhzI7F2tFs_fYHXJvhzCTpLsQr-zWrzdLz8f4Sz4u2m3NvfFfH1f02xYgW1yJvLLB2Rko9Vha-5hpX7BxeV_obX-95SIf9AR-PAEx44pOOJuE93mIHY7fJMt8tGvPKBwS6FJbmHY9EfzOvawoFDo3EgHswoq5AkVpDCV1dBYR8sKlZuLqiP7wdSNMOUQqYexNJqpn2spr8B0rO2NUDI5-3Ba97qud_4Do5Cylw?type=png)](https://mermaid.live/edit#pako:eNqFkbFKA0EQhl9lmCqB3AscIuhFRVAQIzZuiiU7MQd7u8c6K4aQzlJQFLRM5QPYiT5U8gjO5Q4Lj8Sphm8-fgb-GY68IUwRroMuJ3ByrhzI7F2tFs_fYHXJvhzCTpLsQr-zWrzdLz8f4Sz4u2m3NvfFfH1f02xYgW1yJvLLB2Rko9Vha-5hpX7BxeV_obX-95SIf9AR-PAEx44pOOJuE93mIHY7fJMt8tGvPKBwS6FJbmHY9EfzOvawoFDo3EgHswoq5AkVpDCV1dBYR8sKlZuLqiP7wdSNMOUQqYexNJqpn2spr8B0rO2NUDI5-3Ba97qud_4Do5Cylw)

#### FireWall
[![](https://mermaid.ink/img/pako:eNqFkcFKw0AQhl9lmFMDzQsEETS1IiiIFS9uD0t3agOb3bBu1FJ68ygoKnrwEDz0AbyJPpR5BCdNFDVQ97T8-_3_zPLPcGQVYYRw4mQ2gd0DYYDPxnFZ3L6Dlpm32RDWwnAdep2yeLz8eL2GfWcvpkFNbjL5sFiq8bASVsExw3cvEJPOtXQrc_sV-gaHR_-FClMb_j6G7NjqsHh1AzvGkzPkgya8rQPTVcL9oiyenjmFwX7i6FxqHXyNaNvYtf09d0DujFwzoiXDj4Vq5NdazV-wiym5VCaKS5lVokA_oZQERnxVNJa59gKFmTMqc28HUzPCyLucuphnSnrqJZLbTDEaS33KKqnEW7dXF73se_4J01-5cg?type=png)](https://mermaid.live/edit#pako:eNqFkcFKw0AQhl9lmFMDzQsEETS1IiiIFS9uD0t3agOb3bBu1FJ68ygoKnrwEDz0AbyJPpR5BCdNFDVQ97T8-_3_zPLPcGQVYYRw4mQ2gd0DYYDPxnFZ3L6Dlpm32RDWwnAdep2yeLz8eL2GfWcvpkFNbjL5sFiq8bASVsExw3cvEJPOtXQrc_sV-gaHR_-FClMb_j6G7NjqsHh1AzvGkzPkgya8rQPTVcL9oiyenjmFwX7i6FxqHXyNaNvYtf09d0DujFwzoiXDj4Vq5NdazV-wiym5VCaKS5lVokA_oZQERnxVNJa59gKFmTMqc28HUzPCyLucuphnSnrqJZLbTDEaS33KKqnEW7dXF73se_4J01-5cg)

#### WebServer
[![](https://mermaid.ink/img/pako:eNqrVkrOT0lVslJSSC9KLMhQ8AmKyVMAAsfoD_Mn7VZIzslMzSspjlWw0dW1U3DR0Pgwv2eCgmdeSWpRXmqJpiZEsRNQ8bSl73f0E6ceoglTEqQJqMsVaFr_GoXg1KKy1KJYqA4opaSjlJtalJuYmQJ0cjVIMEapJCM1NzVGyQrITElNSyzNKYlRismrBSpNLC3JD67MS1ayKikqTdVRKi1ISSxJdclMBPo1V8kqLTGnGCiampJZkl_kCwkGcGjUAgDF7GAD?type=png)](https://mermaid.live/edit#pako:eNqrVkrOT0lVslJSSC9KLMhQ8AmKyVMAAsfoD_Mn7VZIzslMzSspjlWw0dW1U3DR0Pgwv2eCgmdeSWpRXmqJpiZEsRNQ8bSl73f0E6ceoglTEqQJqMsVaFr_GoXg1KKy1KJYqA4opaSjlJtalJuYmQJ0cjVIMEapJCM1NzVGyQrITElNSyzNKYlRismrBSpNLC3JD67MS1ayKikqTdVRKi1ISSxJdclMBPo1V8kqLTGnGCiampJZkl_kCwkGcGjUAgDF7GAD)

#### Database Server
[![](https://mermaid.ink/img/pako:eNqFkc1Kw0AUhV_lclcNNC8QRNC0_oCCWNGF08Vtc2sDk0mYTMRSunMpKAq67ErcFdyJfaj2EbxpSikocVbDOd85M3DG2E8jxgDhxlI2hJNzZUDO3vVy-jwHTZlLsy7s-P4utBvL6dv94usRzmx6N_Iqcl_I1_eVGnZLoQ4OBX75hJB1ocnW9h6U6DdcXP5XqkwVaDfEfXiCY-PYGnaeJ5HDTeKKe9Bhe8t2_cCfFvgSWjdV2FZfTU5SRxu9RY56lDPk2--V_sfsl1n7SWWwiQnbhOJIRhqXokI35IQVBnKNeECFdgqVmQhKhUs7I9PHwNmCm1hkETluxSTrJhgMSOeichS71J5Ww6_2n_wA42a_Tg?type=png)](https://mermaid.live/edit#pako:eNqFkc1Kw0AUhV_lclcNNC8QRNC0_oCCWNGF08Vtc2sDk0mYTMRSunMpKAq67ErcFdyJfaj2EbxpSikocVbDOd85M3DG2E8jxgDhxlI2hJNzZUDO3vVy-jwHTZlLsy7s-P4utBvL6dv94usRzmx6N_Iqcl_I1_eVGnZLoQ4OBX75hJB1ocnW9h6U6DdcXP5XqkwVaDfEfXiCY-PYGnaeJ5HDTeKKe9Bhe8t2_cCfFvgSWjdV2FZfTU5SRxu9RY56lDPk2--V_sfsl1n7SWWwiQnbhOJIRhqXokI35IQVBnKNeECFdgqVmQhKhUs7I9PHwNmCm1hkETluxSTrJhgMSOeichS71J5Ww6_2n_wA42a_Tg)


### Hospedagem de Sites
- Contratar um servidor para hospedar o seu site.
- existem varia empresas q oferecem hospedagem para sites.

## Aula 4 - liguagem de programação
### O que são linguagens de Programação?
Linguagem de programação é uma linguagem escrita e formal que especifica um conjunto de instruções e regras para serem usadas para gerar programas (software)

#### 10 principais linguagens de programação em 2023 segundo a hostinger:
1. Python
2. C#
3. C++
4. JavaScript
5. PHP
6. Swift
7. Java
8. Go
9. SQL
10. Ruby

### Linguagem Server-Side
- São liguagens que rodam no servido.
- Cada linguagem tem sua caracteristica

#### Exemplo de Linguagens Server-Side
- PHP
- Java
- JavaScript
- Ruby
- C#

### Linguagem Client-Side
Linguagens que são executadas do lado do client.
- JavaScript

O java script roda tanto do lado do servidor como do lado do cliente.
Isso ocorre pq a google criou uma engine chamada V8, que eh um mecanismo de leitura q interpleta java script.
Para rodar o Javascript no back end foi criado o NodeJS, que ele vai rodar o V8 no servidor.
Quem roda verdadeiramente o JavaScript eh o V8, seja do lado do cliente ou do lado do servidor.

[site V8](https://v8.dev)

### HTML não é linguagem de Programação
- não é uma linguagem de programação
- HTML é uma linguagem de Marcação
- Textos delimitados por nomes que o navegador conegue interpletar.
- Cada nome desses delimitadores tem uma função e comportamento específicos.


