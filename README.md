#FRP-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Felipe Ruiz

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'frp-product-card'
```

```
<ProductCard
    key={product.id}
    product={product}
    initialValues={{
    count: 4,
    maxCount: 10,
    }}
>
    {({ reset, count, increaseBy, isMaxCountReached, maxCount }) => (
    <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
    </>
    )}
</ProductCard>
```
