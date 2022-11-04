# llqd-Product-Card 

Este es un paquete de pruebas de despliegue en NPM

### luca Luzzi

## Ejemplo:

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'llqd-product-card';
```

```
      <ProductCard 
        product={ product }
        initialValues={{
          count: 0,
          // maxCount: 10
        }}
      >
        {
          ({ reset, increaseBy, count, isMaxCountReached }) => (
            <>
              <ProductImage />
              <ProductTitle />
              <ProductButtons />
            </>
          )
          }
      </ProductCard> 
      ```