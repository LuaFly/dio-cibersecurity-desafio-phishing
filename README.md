# dio-cibersecurity-desafio-phishing


<style>
	.tabela {
		border:2px solid #C0C0C0;
		border-collapse:collapse;
		padding:5px;
	}
	.tabela th {
		border:2px solid #C0C0C0;
		padding:5px;
		background:#F0F0F0;
	}
	.tabela td {
		border:2px solid #C0C0C0;
		padding:5px;
	}
</style>
<table class="tabela">
                        
                            	<caption></caption>	<thead>	<tr>		<th>Descrição</th>
                                    
                                    
                                
                                		<th>Comando</th>
	</tr>	</thead>	<tbody>	<tr>
		<td><span style="color: rgb(31, 35, 40); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, &quot;Noto Sans&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px;">Acesso root</span><br></td>
                                    
                                    
                                    
                                
                                		<td>&nbsp; Sudo su</td>
	</tr>
                                	<tr>
                                
                                    		<td><span style="color: rgb(31, 35, 40); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, &quot;Noto Sans&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px;">Iniciando o setoolkit</span></td>
		<td>&nbsp;setoolkit</td>
	</tr>
                                
                                	<tr>
                                
                                    		<td><span style="color: rgb(31, 35, 40); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, &quot;Noto Sans&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px;">Tipo de ataque</span><br></td>
                                    
                                    
                                    
                                
                                		<td>&nbsp;Social-Engineering Attacks</td>
	</tr>
                                
                                	<tr>
                                    
                                    		<td><span style="color: rgb(31, 35, 40); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, &quot;Noto Sans&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px;">Vetor de ataque</span><br></td>
                                    
                                    
                                    
                                
                                		<td>&nbsp;Web Site Attack Vectors</td>
	</tr>
                            	<tr>
		<td><span style="color: rgb(31, 35, 40); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, &quot;Noto Sans&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px;">Método de ataque</span><br></td>
		<td>&nbsp;Credential Harvester Attack Method</td>
	</tr>
	<tr>
		<td><span style="color: rgb(31, 35, 40); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, &quot;Noto Sans&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px;">Método de ataque</span><br></td>
		<td>&nbsp;Site Cloner</td>
	</tr>
	<tr>
		<td><span style="color: rgb(31, 35, 40); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, &quot;Noto Sans&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px;">URL para clone</span><br></td>
		<td>&nbsp;http://www.linkedin.com</td>
	</tr>
	<tbody>
                        </table>


1- Precisamos estar como root no kali
![image](https://github.com/LuaFly/dio-cibersecurity-desafio-phishing/assets/42554771/2c1d2f87-2c39-4402-81da-4512e2c9ab88)

2- iniciamos o setoolkit
![image](https://github.com/LuaFly/dio-cibersecurity-desafio-phishing/assets/42554771/10f85203-70d6-4258-b251-917c5b8e579e)
![image](https://github.com/LuaFly/dio-cibersecurity-desafio-phishing/assets/42554771/9bbf8517-6a91-4631-99f3-5a1038266b91)

3- Vamos escolher o numero 1, ataques de engenharia social
![image](https://github.com/LuaFly/dio-cibersecurity-desafio-phishing/assets/42554771/82745884-488b-4ed2-b2da-3591439db14a)

4- Depois o vetor de ataque, nesse caso o numero 2, website
![image](https://github.com/LuaFly/dio-cibersecurity-desafio-phishing/assets/42554771/a626839a-1f4f-4f99-b448-9dfe65e78e80)

5- Apareceu algumas opções, vamos selecionar o numero 3, captura de credencial. 
![image](https://github.com/LuaFly/dio-cibersecurity-desafio-phishing/assets/42554771/80f8f2f6-8e1d-4f9b-af68-af5d1f006bca)

6- Agora vamos selecionar o numero 2, clone de site
![image](https://github.com/LuaFly/dio-cibersecurity-desafio-phishing/assets/42554771/5cd64d67-6f70-4250-b623-3eab1a51b625)

7- Vamos confirmar o Ip e dar enter
![image](https://github.com/LuaFly/dio-cibersecurity-desafio-phishing/assets/42554771/9cee366f-dcc2-445f-8bc4-7ec716c64f90)

8- Depois é só colocar a url que deseja clonar, nesse caso o linkedin
![image](https://github.com/LuaFly/dio-cibersecurity-desafio-phishing/assets/42554771/812fdfa2-bda4-4c15-9df6-9b858029599e)

Como podemos ver, ele já está disponível, vou acessar o linkedin pelo ip:
![image](https://github.com/LuaFly/dio-cibersecurity-desafio-phishing/assets/42554771/2d7841a8-495f-45e7-aff8-dde3213aaf05)

E ao voltarmos a tela do setoolkit teremos as informações do usuário e senha:
![image](https://github.com/LuaFly/dio-cibersecurity-desafio-phishing/assets/42554771/d359967e-f158-4f32-b428-fcfbeda8db52)
