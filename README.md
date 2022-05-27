# ELC-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Eduardo Loo

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'elc-product-card';
```

```
<ProductCard  key={ product.id }
                product={ product }
                initialValues={{
                count: 6,
                //maxCount: 10
                }}
    >
    {
        ( { reset, count, isMaxCountReached, increaseBy, maxCount } ) => (
        <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
        </>                
        )
    }
</ProductCard>
```