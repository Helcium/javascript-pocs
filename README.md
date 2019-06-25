# javascript-pocs
POCs with some solutions for JS


<pre>
<a th:onclick="'javascript:openNewTab(\'/app/relatorios/' + ${relatorio.id} + '\');'" 
  href="#">
  <span title="Gerar e visualizar Relatório" 
    class="glyphicon glyphicon-eye-open text-success" 
    aria-hidden="true">
  </span>
</a>

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
