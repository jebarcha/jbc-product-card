# JBC-Product-Card

This is a deploy test package in NPM

### Jose de Jesus Barajas

## Example
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'jbc-product-card'
```

```
<ProductCard 
    product={product}
    initialValues={{
        count: 6,
        //maxCount: 10
    }}
>
    {
        ( { reset, count, increaseBy, maxCount, isMaxCountReached } ) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```