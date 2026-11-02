# naranjax_noviembre

Imágenes y plantillas de email de la campaña de cobranza Naranja X · Noviembre 2026 (lotes El Buen Fin e institucional).

- `NX_buenfin_*.jpg` y `NX_institucional_*.jpg`: banners de cabecera por segmento (1200 px de ancho).
- `icono_spei.png`, `icono_tienda.png`, `icono_referencia.png`: íconos de formas de pago.
- `Naranja_X.png`: logo del encabezado.
- `emails/`: los 36 emails en HTML minificado. Leen las imágenes desde `https://raw.githubusercontent.com/josmarvelasquez-ctrl/naranjax_noviembre/main/`.

Variables usadas: `@nombre`, `@fecha_de_vencimiento`, `@dias_de_mora`, `@saldo_de_deuda`, `@saldo_provisionado`, `@info_1`, `@info_2`. El botón de pago apunta a `URL_BOTON_PAGO` hasta definir el destino.
