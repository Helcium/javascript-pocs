# javascript-pocs
POCs with some solutions for JS


<pre>

&#x3C;a th:onclick=&#x22;&#x27;javascript:openNewTab(\&#x27;/app/relatorios/&#x27; + ${relatorio.id} + &#x27;\&#x27;);&#x27;&#x22; 
  href=&#x22;#&#x22;&#x3E;
  &#x3C;span title=&#x22;Gerar e visualizar Relatorio&#x22; 
    class=&#x22;glyphicon glyphicon-eye-open text-success&#x22; 
    aria-hidden=&#x22;true&#x22;&#x3E;
  &#x3C;/span&#x3E;
&#x3C;/a&#x3E;
</pre>
<pre>
<script type="text/javascript">
	function openNewTab(url){
			
		var win = window.open(url);		
		win.addEventListener('load', function () { 
			setTimeout(function () {
				location.reload(true);
			}, 2000);
		});
			
	}
</script>
</pre>
