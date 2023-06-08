**Desafío Tienda Joyas - Johhan Urrutia**

Cmd en terminal:

npm i = instalación de dependencias
npm run dev = Levantar Servidor LocalHost:3000

**Petición GET /joyas - Uso de Querystrings:**

Querystrings:
* limit - page - order_by

**Petición GET /joyas/filtros - Uso de Querystrings:**

    Querystring:

    Uso de filtro en query strings con operadores:
    filters[propiedad][$operador]

    Ejemplo:
    filters[precio][$gt]

    Abreviaturas de operadores insertos en función para consulta en querystring:
    $eq: "=", 
    $gt: ">", 
    $gte: ">=", 
    $lt: "<", 
    $lte: "<=", 
    $ne: "!=", 
