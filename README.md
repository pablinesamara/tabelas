# tabelas
criando tabelas no html
<!doctype html>
 
<!DOCTYPE html>
<html>
	
	<head>
			<title>Página principal</title>
		<meta charset="utf-8">
	</head>
	
	<body>

		<table border="2" width= "100%">
			
				<tr>
					<th>Código</th>
					<th>Produto</th>
					<th>Preço</th>
				</tr>
				
				<tr>
					<td>001</td>
					<td>Notebook</td>
					<td>R$ 2.500,99</td>
				</tr>

				<tr>
					<td>002</td>
					<td>Tablet</td>
					<td>R$ 999,99</td>
				</tr>
				<tr>
					<td rowspan="2">Desconto</td>
					<td colspan="2">Cupom 1-R$10</td>
					</tr>
					<tr>
					<td colspan="2">Cupom2 -R$12</td>
					
				</tr>
				<tr>
					<td>Total:</td>
					<td colspan="2">R$3.478,98</td>
				</tr>


		</table>
		

	 
	</body>
</html>
