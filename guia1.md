# Ejercicio 1
_P|P|1_:
## Hipotesis:
| Variable      | Unidad         |
| ------------- |----------------|
| $\lambda = 24$|$\frac{cl}{h}$  |
| $T_s = 2$     |$\frac{min}{cl}$|
| $\mu = 1/2$   |$\frac{cl}{min}$|

a) Número de clientes en la sección:
> $$L = \frac{\lambda}{\mu - \lambda} = \frac{0.4}{0.1} = 4$$
b) Permanencia promedio de un cliente en la sección
> $$W = \frac{1}{\mu - \lambda} = \frac{1}{0.1} = 10 [\frac{min}{cl}]$$
c) Probabilidad de que el sastre esté desocupado
> $$P(0) = 1 - \rho = 1 - \frac{\lambda}{\mu} = \frac{0.4}{0.5} = 0.8$$
d) Número promedio de clientes que están esperando recibir el servicio
> $$W_c = \frac{\lambda}{\mu(\mu - \lambda)} = \frac{0.4}{0.5(0.5 - 0.4)} = 8$$

# Ejercicio 2
_P|P|1_
## Hipotesis:
| Variable      | Unidad         |
| ------------- |----------------|
| $\lambda = 4$ |$\frac{cl}{h}$  |
| $T_s = 6$     |$\frac{min}{cl}$|
| $\mu = 1/6$   |$\frac{cl}{min}$|

a)Probabilidad que el taller esté vacío
> $$P(0) = 1 - \rho = 1 - \frac{\lambda}{\mu} = \frac{4}{10} = 0.4$$
b)Probabilidad de que 3 clientes estén en el taller
> $$P(3) = \rho^3P(0) = (\frac{\lambda}{\mu})^3(1 - \frac{\lambda}{\mu}) = (\frac{\lambda}{\mu})^3 - (\frac{\lambda}{\mu})^4 = 0.4^3 - 0.4^4 \approx 0.0384$$
c) Probabilidad de encontrar por lo menos 1 cliente en el taller
> $$P(n \ge 1) = 1 - P(0) = 1 - 0.4 = 0.6$$
d) Nro. promedio de clientes en el taller
> $$L = \frac{\lambda}{\mu - \lambda} = \frac{4}{10 - 4} \approx 0.67$$
e) Tiempo promedio que un cliente debe permanacer en el taller
> $$W = \frac{1}{\mu - \lambda} = \frac{1}{10 - 4} \approx 0.167 [\frac{h}{cl}]$$
f) El número promedio de clientes que esperan ser atendidos
> $$L_c = \frac{\lambda^2}{\mu(\mu - \lambda)} = \frac{16}{10(10 - 4)} \approx 0.267$$
g) Tiempo promedio que un cliente debe esperar para ser atendido
> $$W_c = \frac{\lambda}{\mu(\mu - \lambda)} = \frac{4}{10(10 - 4)} \approx 0.067$$

# Ejercicio 3
_P|P|1_
## Hipotesis:
| Variable      | Unidad         |
| ------------- |----------------|
| $T_a = 8$ |$\frac{min}{cl}$  |
| $\lambda = \frac{1}{8}$ |$\frac{cl}{min}$  |
| $T_s = 2$     |$\frac{min}{cl}$|
| $\mu = 1/2$   |$\frac{cl}{min}$|
a) Probabilidad de esperar
> $$ P(0) = 1 - \rho = 1 - \frac{\lambda}{\mu} = 1 - \frac{1/8}{1/2} = 0.75$$
> $$ P(1) = \rho^1 P(0) = (0.25)(0.75) = 0.1875$$
> $$P(n \ge 2) = 1 - P(0) - P(1) = 0.0625$$
b) Longitud promedio de la cola
> $$L_c = \frac{\lambda^2}{\mu(\mu - \lambda)} = \frac{0.0156}{0.5(0.5 - 1/8)} = 0.625$$

 