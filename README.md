<p align="center">
  <img src="https://github.com/guidospadavecchia/BluePy/blob/main/static/icon.png">
</p>

*** 
<p align="center">
  <i>Cotizaciones blue de Dólar, Euro y Real</i>
</p>  

## Endpoints

### Dólar
| Método | Endpoint | Descripción |
| ------ | ------ | ------ |
| GET | /api/dolar/oficial | Cotización del dólar oficial |
| GET | /api/dolar/blue | Cotización dólar blue |

### Euro
| Método | Endpoint | Descripción |
| ------ | ------ | ------ |
| GET | /api/euro/oficial | Cotización del dólar oficial |
| GET | /api/euro/blue | Cotización dólar blue |

### Real
| Método | Endpoint | Descripción |
| ------ | ------ | ------ |
| GET | /api/real/oficial | Cotización del dólar oficial |
| GET | /api/real/blue | Cotización dólar blue |

#### Respuesta

```javascript
{
    fecha: "2021/06/30 23:26:42",
    compra: "165.41",
    venta: "172.63"
}
```

### Otros
| Método | Endpoint | Descripción |
| ------ | ------ | ------ |
| GET | /api/ping | Devuelve '*pong*' si el sitio está activo |

## Licencia
Este proyecto es ***100% libre y open-source***. Está licenciado bajo la [MIT License](https://github.com/guidospadavecchia/BluePy/blob/main/LICENSE).

*** 
**Datos recopilados de https://www.paralelohoy.com.ar*
