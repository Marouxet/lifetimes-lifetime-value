# Lifetime Value
# Modeloado de Customer Lifetime Value (CLTV)

El poryecto consiste en tomar información transaccional de una base de datos en Snowflake y utilizar la librería Lifetimes para calcular el CLTV para clientes con más de una transacción.

La información transaccional proviene de Google Analytics para ventas online y de información de facturación para ventas en tienda física.

Los ususarios están registrados con una CUSTOMER_KEY hasheada implementada por el cliente.

El objetivo del proyecto es enviar a Google Ads una lista de ususarios (identificados con el GCLID) y su CLTV, para luego crear audiencias de alto valor para hacer Lookalikie en campañas de marketing.

El proceso de envío a Google Ads no está incluido en el repositorio.