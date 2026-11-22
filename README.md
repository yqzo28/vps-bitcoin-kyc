# VPS con Bitcoin: ¿desde cuánto, hace falta KYC y qué plan aguanta un nodo? (planes, precios en euros y la letra pequeña del pago con BTC)

Ava Hosting vende VPS desde **2 € al mes** y acepta Bitcoin en el checkout a través de la pasarela Cryptomus, junto a Monero, Litecoin, USDT, USDC y una docena larga de monedas más. Para crear la cuenta solo hace falta un correo: en el proceso de pedido que describe su propia base de conocimiento no hay ningún paso de verificación de identidad ni subida de documentos. Lo que no vas a encontrar publicado es una política de reembolso ni un plan con disco suficiente para un nodo de Bitcoin en modo archivo.

Ese es el resumen útil. Lo que sigue desglosa los trece planes del catálogo con sus precios en euros, cómo se paga exactamente con BTC, qué significa "ilimitado" en un VPS de 2 €, cuánto disco necesitas según lo que vayas a montar y en qué se diferencia Ava de lo que ofrecen otras tiendas del mismo nicho.

## Resumen para quien decide rápido

> **Uso más común:** el plan **Self-hosted Start, 2 €/mes** (1 vCPU, 1 GB de RAM, 15 GB NVMe) sobra para una cartera, un Electrum Server o una VPN, y es el punto de entrada más barato del catálogo.
> **Si vas a sincronizar un nodo podado de Bitcoin Core:** salta al **VPS Basic, 10 €/mes** con 4 GB de RAM y 50 GB NVMe. Con 1 GB de RAM el nodo arranca, pero el rendimiento durante la sincronización se resiente.
> **Si buscas un nodo archival:** ninguno de los planes llega. El tope son 200 GB NVMe y un nodo completo sin poda pide del orden de 1 TB.

👉 [Ver los planes de Ava Hosting desde 2 € al mes](https://my.ava.hosting/aff.php?aff=15562)

## Todos los planes que Ava Hosting muestra ahora

El catálogo está partido en dos familias con nombres distintos y recursos que se solapan. La línea *Self-hosted* solo lista CPU, RAM, disco y tráfico; la línea *VPS/VDS* añade en su ficha protección DDoS, backup semanal, panel de control, SLA del 99,9% y soporte 24/7. Antes de elegir conviene mirar las dos, porque hay parejas con el mismo precio y distinto disco.

**Línea Self-hosted (precios mensuales, EUR)**

| Plan | vCPU · RAM · NVMe | Puerto / Tráfico | Precio | Ciclo | Pedir |
| --- | --- | --- | --- | --- | --- |
| Start | 1 · 1 GB · 15 GB | n/d · ilimitado | 2,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| Mini | 1 · 2 GB · 25 GB | n/d · ilimitado | 5,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| Basic | 2 · 4 GB · 50 GB | n/d · ilimitado | 10,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| Pro | 4 · 8 GB · 100 GB | n/d · ilimitado | 20,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| Business | 6 · 12 GB · 150 GB | n/d · ilimitado | 30,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| Power | 8 · 16 GB · 200 GB | n/d · ilimitado | 40,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |

**Línea VPS/VDS (precios mensuales salvo el Nano, EUR)**

| Plan | vCPU · RAM ECC · NVMe | Puerto / Tráfico | Precio | Ciclo | Pedir |
| --- | --- | --- | --- | --- | --- |
| VPS Nano | 1 · 512 MB · 20 GB | 100 Mbps · ilimitado | 11,00 € | **anual** | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| VPS One | 1 · 2 GB · 25 GB | 1 Gbps · ilimitado | 5,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Basic | 2 · 4 GB · 50 GB | 1 Gbps · ilimitado | 10,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Lucky | 2 · 6 GB · 70 GB | 1 Gbps · ilimitado | 15,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Power | 4 · 8 GB · 90 GB | 1 Gbps · ilimitado | 20,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Extra | 6 · 12 GB · 120 GB | 1 Gbps · ilimitado | 30,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Ultra | 8 · 16 GB · 160 GB | 1 Gbps · ilimitado | 40,00 € | mensual | [ Ver plan](https://my.ava.hosting/aff.php?aff=15562) |

Tres cosas que se ven al poner las tablas juntas. El **VPS Nano a 11 €/año** es el precio más bajo de todo el catálogo, pero su ficha marca 0 unidades disponibles y el puerto 25 cerrado, así que si lo que buscas es correo saliente olvídate. El **Power de 40 €** lleva 200 GB NVMe y es el techo de disco de la casa; su gemelo VPS Ultra, por el mismo dinero, se queda en 160 GB. Y el **Self-hosted Start de 2 €** no tiene equivalente en la línea VPS, que arranca en 5 €.

Ninguno de estos precios es una oferta con descuento: son tarifas de lista. Eso importa, y mucho, en el siguiente apartado.

## Cómo se paga un VPS con Bitcoin, paso a paso

Ava no cobra en BTC directamente contra su propia wallet. Usa **Cryptomus** como procesador, y eso cambia dos cosas: el pago pasa por un intermediario y la lista de monedas depende de lo que esa pasarela soporte en cada momento.

El recorrido, según la base de conocimiento oficial, es este:

1. Entra en el panel de cliente y elige "Order New Services".
2. Selecciona el servicio, marca la casilla de aceptación de los términos y baja a los métodos de pago.
3. Escoge "All Crypto Payments" y luego "Pay with Cryptomus".
4. Te redirige a Cryptomus, donde eliges **moneda y red**.
5. Pagas y esperas. El pedido llega al correo que registraste en **20–30 minutos** con los datos de acceso.

Las monedas disponibles en esa pasarela incluyen BTC, XMR, LTC, USDT (BEP20, TRC20 y ERC20), USDC, SOL, BNB, TRX, MATIC, DASH, DOGE, TON, BCH, DAI y unas cuantas más. Que existan no significa que todas estén activas para tu pedido: la lista se confirma en la pantalla de pago.

Los 20–30 minutos de espera cuadran con el funcionamiento de la red. Bitcoin produce un bloque cada **10 minutos** aproximadamente, y los importes pequeños se suelen acreditar con la primera confirmación. Si pagas en USDT por TRC20, el tiempo será otro. La espera hasta tener la máquina encendida no es comparable entre proveedores cuando uno cuenta la confirmación on-chain y otro solo el aprovisionamiento.

El error caro aquí es de red, no de moneda. Mandar USDT por ERC20 cuando el pedido espera BEP20, o elegir BTC en una dirección que era de Lightning, deja el dinero en el limbo. Confirma la combinación exacta de token y red antes de enviar; esa precaución la repiten todas las tiendas del sector porque el fallo lo paga el cliente.

👉 [Abrir el pedido de Ava Hosting y elegir pago con Bitcoin](https://my.ava.hosting/aff.php?aff=15562)

## La letra pequeña: 2 € al mes no es el coste de nada

Un VPS de 2 € mensuales son **24 € al año**, y eso es lo que vas a pagar de verdad porque Ava no muestra precio de renovación distinto al de alta. Ahí lleva ventaja sobre el resto del mercado, donde el precio de escaparate suele ser una promoción de primer periodo.

El caso más claro es Cloudzy: anuncia **2,48 $/mes** con un 50% de descuento sobre 4,95 $/mes. Es decir, el segundo año pagas el doble si no hay otra promo. NoctHost juega con otra regla, la del saldo prepago: la recarga mínima son 20 $ y **no es reembolsable**, quede lo que quede en la cuenta. Y el reembolso de 14 días de Cloudzy existe, pero si pagaste en BTC te lo devuelven en BTC calculado sobre el valor en dólares original, sin asumir la variación del precio.

Con Ava esa comparación no se puede cerrar porque **no hay política de reembolso publicada** en las páginas de planes ni en la base de conocimiento que hemos revisado. Una reseña de terceros sobre el proveedor menciona 30 días de garantía para pedidos nuevos; no lo hemos podido confirmar en una página oficial. Antes de mandar sats, abre un ticket y pide por escrito dos cosas: condiciones de devolución y qué pasa si el servicio no arranca.

Dos detalles más que solo aparecen en las fichas. Ava opera desde Moldavia según esa misma reseña de terceros, y sus páginas de planes no publican la ubicación del centro de datos, algo que decide la latencia si vas a conectar por SSH desde España o Latinoamérica. Y el tráfico se anuncia como ilimitado sin publicar una política de uso razonable; para una web pequeña da igual, para un nodo que sirve cientos de GB al mes conviene preguntar antes.

## ¿Nodo de Bitcoin, cartera o VPN? Cuánto disco hace falta

Aquí se decide el plan, y la respuesta depende de una sola cosa: si vas a guardar la cadena entera o solo una parte.

**Nodo podado.** Bitcoin Core con `prune` descarta bloques antiguos y se conforma con bastante menos espacio. Cloudzy, en sus preguntas frecuentes, sitúa un nodo podado en un plan de 4 GB de RAM y 120 GB NVMe. Con ese criterio, el **VPS Basic de Ava a 10 €** (4 GB, 50 GB NVMe) es el punto de partida razonable, y el **VPS Lucky a 15 €** (6 GB, 70 GB) da margen para el crecimiento de la cadena y para tener algo más corriendo en la misma máquina. El Self-hosted Start de 2 € sirve para sincronizar, pero 1 GB de RAM se queda corto en cuanto el nodo empieza a recibir mempool.

**Nodo archival.** Necesitas del orden de **1 TB de almacenamiento**, según la propia referencia de Cloudzy. Ava no llega ni a la quinta parte: su máximo son 200 GB. Si tu plan es montar un nodo completo con `txindex` y servir la red, tendrás que buscar otro proveedor, y desconfía de las etiquetas: la misma página de Cloudzy marca su plan de 4 GB y 120 GB como "Full archival Core + Lightning" mientras su FAQ dice que para archivo hacen falta al menos 1 TB. La contradicción está en la fuente, no en la lectura.

**Cartera, Electrum Server, Lightning o VPN.** Con 1 GB de RAM y 15 GB de disco hay margen. Un servidor Electrum o un nodo de Lightning con LND no necesitan la cadena completa y el plan de 2 € cumple.

Sobre el ancho de banda, un dato que casi nadie publica y que sí está en la documentación de Cloudzy: un nodo archival con la configuración por defecto mueve entre **200 y 500 GB mensuales de salida** cuando sirve a la red. Con "tráfico ilimitado" de por medio no deberías chocar con un límite, pero es la clase de cifra que conviene tener a mano si el proveedor te escribe un día hablando de uso excesivo.

👉 [Ver el plan de 4 GB y 50 GB NVMe para un nodo podado](https://my.ava.hosting/aff.php?aff=15562)

## Minería: la política que casi nadie publica

Comprar un VPS para minar es una idea con fecha de caducidad, y no por la rentabilidad, sino porque muchos proveedores lo prohíben en su política de uso aceptable. Las tres posturas que se ven en el sector son incompatibles entre sí, así que generalizar sale caro.

Arct Cloud lo dice sin rodeos: la minería de criptomonedas está **prohibida** en sus servidores según su AUP. Mynymbox también la prohíbe, y añade que sí permite nodos de Bitcoin y servicios relacionados. LightNode va en la dirección contraria y en sus preguntas frecuentes define un VPS de Bitcoin como aquel configurado para actividades como "mining, running a node, or hosting a wallet". Cloudzy se queda en un terreno ambiguo: dice que puedes instalar lo que corra en Linux y que el software de pool depende del hashrate, con el matiz de que el VPS sirve para orquestar, no para hashear.

Ava Hosting no publica una política de minería en las páginas de planes ni en la documentación revisada. Si el uso que tienes en mente se acerca a eso, pregunta por ticket antes de pagar y guarda la respuesta.

## Comparativa rápida con otras tiendas

Sirve para situar a Ava, no para sustituirla. Todas las cifras son las que mostraba cada página en el momento de la consulta, sin verificar qué precio aplican en la renovación.

| Proveedor | Precio de entrada | Moneda | Identidad | Reembolso | Minería |
| --- | --- | --- | --- | --- | --- |
| Ava Hosting | 2 €/mes (Start) | EUR | solo correo en el flujo de pedido | no publicado | no publicado |
| Cloudzy | 2,48 $/mes (50% off; lista 4,95 $) | USD | no indicado | 14 días, BTC al valor USD original | ambigua |
| NoctHost | 10 $/mes; recarga mínima 20 $ | USD | solo correo, sin KYC | recargas no reembolsables | no indicado |
| Mynymbox | 4 €/mes | EUR | sin KYC, Tor permitido | no indicado | prohibida |

Dos avisos de lectura. Mynymbox cobra en euros y el resto en dólares, así que comparar 4 € con 2,48 $ sin convertir es hacer trampa. Y los precios de entrada no miden lo mismo: NoctHost exige depositar 20 $ por adelantado, mientras que en Ava pagas el mes que consumes.

## Preguntas que aparecen antes de pagar

**¿Cuánto tarda en confirmarse el pago?** Un bloque tarda unos 10 minutos de media y los importes pequeños suelen acreditarse con la primera confirmación. Ava añade el aprovisionamiento y habla de 20–30 minutos hasta recibir los datos por correo.

**¿Puedo pagar con Lightning?** No consta entre las opciones que documenta Ava para Cryptomus. Si necesitas pagos instantáneos por Lightning, este no es el camino.

**¿Me van a pedir DNI o pasaporte?** El flujo descrito no incluye verificación de identidad: cuenta con correo, selección de servicio y pago. No hay subida de documentación en esos pasos.

**¿Puedo entrar por Tor?** No está documentado en las páginas revisadas, a diferencia de Mynymbox, que lo permite expresamente. Pregunta si dependes de ello.

**¿Qué pasa si me equivoco de red al pagar?** El pago se pierde. La combinación de token y red que muestra el checkout es la única válida.

**¿Los backups están incluidos?** La línea VPS/VDS los anuncia semanales en la ficha de cada plan. La línea Self-hosted no los menciona, así que si el respaldo te importa, ese detalle puede justificar los 3 € de diferencia entre Start y VPS One.

**¿Hay stock?** El VPS Nano figura con 0 unidades disponibles. El resto aparece pedible, pero el stock se mueve.

## Cómo elegir según tu caso

Si lo que quieres es una máquina pequeña para una cartera, un Electrum Server o una VPN y pagar con BTC sin dar datos, el **Self-hosted Start de 2 €** es la opción con mejor relación entre precio y fricción de todo el catálogo. Si el plan incluye un nodo podado de Bitcoin Core, sube al **VPS Basic de 10 €**: los 4 GB de RAM y los 50 GB NVMe marcan la diferencia entre sincronizar y sufrir. Para nodo archival, cambia de proveedor; con 200 GB de techo no hay debate. Y si lo que te frena es la privacidad del pago, ten presente que Ava cobra a través de Cryptomus y no contra su propia wallet, un escalón más de intermediación que quien usa BTCPay autohospedado.

Antes de enviar los sats, confirma dos cosas por ticket: la política de devolución y la de minería. Son las dos únicas casillas que Ava no tiene publicadas y las dos que más disgustos dan después.

👉 [Revisar precios y stock actuales de Ava Hosting antes de pagar](https://my.ava.hosting/aff.php?aff=15562)
