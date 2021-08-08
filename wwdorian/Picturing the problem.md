```mermaid
graph LR
shipment delay to manufacturer))
	1.1[production error] --causes--> 1
	1.2[raw materials unavailable] --causes-->1
	1.3[international regulation issue] --causes--> 1
	1.4[[order placement fault]] --causes--> 1
	
	2((labour dissatisfaction))
	2.1[poor work environment] --causes--> 2
	2.2[unfair wage] --causes--> 2
	
	3((delay in production))
	1 --leads to--> 3
	2 --leads to--> 3
	
	4((products quality untested/failed))
	4.1[manufacturer produces hastily]
	4.1 --causes--> 4
	
	5((delay in shipment to the DC))
	3 --leads to--> 5
	4 --leads to--> 5
	
	6((delay in shipment to retailers))
	5 --leads to--> 6
	
	7((transporations))

```