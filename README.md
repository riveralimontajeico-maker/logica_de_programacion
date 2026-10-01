programa
{
	funcao inicio ()
{
	        inteiro tipo
	        real dias,km,popular_dias,popular_km,popular_total,lujo_dias,lujo_km,lujo_total,popular,lujo   
	        escreva("Cuál es el tipo de auto? [1] popular | [2] lujo:")
	        leia(tipo)
	        escreva("Cuántos días va a pagar?")
	        leia(dias)
	        escreva("Cuántos km?")
	        leia(km)
	        
	        se (tipo == 1 e km <= 100)
	        {
	        popular_dias = dias * 90
	        popular_km = km * 0.20
	        popular_total = popular_dias + popular_km
	        escreva("El valor a pagar total es de ", popular_total ," reales")
	        }
	        senao se (tipo == 1 e km > 100)
	        {
	        popular_dias = dias * 90
	        popular_km = km * 0.10
	        popular_total = popular_dias + popular_km
	        escreva("El valor total a pagar es de ", popular_total ," reales")
	        }
	        senao se (tipo == 2 e km <= 200)
	        {
	        lujo_dias = dias * 150
	        lujo_km = km * 0.30
	        lujo_total = lujo_dias + lujo_km
	        escreva("El valor total a pagar es de ", lujo_total ," reales")
	        }
	        senao
	        {
	        lujo_dias = dias * 150
	        lujo_km = km * 0.25
	        lujo_total = lujo_dias + lujo_km
	        escreva("El valor total a pagar es de ", lujo_total ," reales")
	        }
	        
}
}
