# semana-14
def calcular_descuento(monto_total, porcentaje_descuento=10):
    """
    Calcula el descuento aplicado a un monto total.

    Args:
        monto_total (float): El monto total de la compra.
        porcentaje_descuento (float): El porcentaje de descuento (por defecto, 10).

    Returns:
        float: El monto del descuento calculado.
    """
    descuento = (porcentaje_descuento / 100) * monto_total
    return descuento

monto_compra1 = 100
descuento1 = calcular_descuento(monto_compra1)

monto_compra2 = 250
porcentaje_descuento2 = 20
descuento2 = calcular_descuento(monto_compra2, porcentaje_descuento2)

print(f"Monto de la compra 1: ${monto_compra1}")
print(f"Descuento aplicado: ${descuento1}")
print(f"Monto final a pagar: ${monto_compra1 - descuento1}")

print(f"\nMonto de la compra 2: ${monto_compra2}")
print(f"Descuento aplicado: ${descuento2}")
print(f"Monto final a pagar: ${monto_compra2 - descuento2}")
éxito
