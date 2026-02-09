<h1>🚚 Tabela de Frete Diluído por Faixa de Peso (1g → 200kg)</h1>

<p>
Este projeto em Python gera automaticamente uma
<strong>planilha completa de fretes diluídos</strong>, considerando:
</p>

<ul>
  <li>Pesos de <strong>1g até 200.000g (200 kg)</strong></li>
  <li><strong>Faixas progressivas de peso</strong></li>
  <li>Diferentes <strong>categorias de preço do produto</strong></li>
  <li>Exportação direta para <strong>Excel pronto para uso</strong></li>
</ul>

<hr/>

<h2>📊 O que o script faz</h2>

<ul>
  <li>Cria uma tabela com <strong>200.000 linhas</strong> (uma para cada grama)</li>
  <li>Associa cada peso à <strong>faixa logística correspondente</strong></li>
  <li>Aplica automaticamente o <strong>valor de frete da categoria</strong></li>
  <li>Gera o arquivo final: <code>frete_diluido.xlsx</code></li>
</ul>

<p>
Pronto para uso em <strong>Excel, Google Sheets e análises de margem</strong>.
</p>

<hr/>

<h2>🧠 Estrutura de cálculo</h2>

<h3>1️⃣ Faixas de peso</h3>

<p>O frete é definido por intervalos em gramas:</p>

<table>
  <tr>
    <th>Faixa</th>
    <th>Peso</th>
  </tr>
  <tr><td>1</td><td>1g – 300g</td></tr>
  <tr><td>2</td><td>301g – 500g</td></tr>
  <tr><td>3</td><td>501g – 1.000g</td></tr>
  <tr><td>…</td><td>…</td></tr>
  <tr><td>22</td><td>150.001g – 200.000g</td></tr>
</table>

<p>Inclui suporte para <strong>produtos acima de 150 kg</strong>.</p>

<h3>2️⃣ Categorias de preço</h3>

<ul>
  <li>Até R$79 / Usado / Grátis</li>
  <li>R$79 a R$99,99</li>
  <li>R$100 a R$119,99</li>
  <li>R$120 a R$149,99</li>
  <li>R$150 a R$199,99</li>
  <li>Mais de R$200</li>
</ul>

<p>
Isso permite simular <strong>frete subsidiado, frete embutido no preço e estratégias de margem</strong>.
</p>

<hr/>

<h2>📦 Estrutura da planilha gerada</h2>

<ul>
  <li><strong>Peso em gramas</strong></li>
  <li><strong>Valor de frete</strong> para cada categoria</li>
</ul>

<p><strong>Total:</strong> 200.000 linhas × 6 categorias de frete</p>

<hr/>

<h2>🚀 Como executar</h2>

<h3>1. Instalar dependências</h3>

<pre><code>pip install pandas openpyxl</code></pre>

<h3>2. Rodar o script</h3>

<pre><code>python gerar_frete_diluido.py</code></pre>

<h3>3. Resultado</h3>

<pre><code>frete_diluido.xlsx</code></pre>

<hr/>

<h2>🛠️ Possíveis melhorias futuras</h2>

<ul>
  <li>Interface web para consulta por peso</li>
  <li>Integração com calculadora de margem</li>
  <li>Importação automática de novas tabelas logísticas</li>
  <li>Dashboard em Power BI ou Streamlit</li>
</ul>

<hr/>

<h2>📄 Licença</h2>

<p>
Uso livre para fins <strong>educacionais, comerciais e analíticos</strong>.<br/>
Contribuições são bem-vindas.
</p>
