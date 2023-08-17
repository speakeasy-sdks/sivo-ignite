<!-- Start SDK Example Usage -->


```typescript
import { SivoIgnite } from "sivo-ignite";
import { CreatePetsResponse } from "sivo-ignite/dist/sdk/models/operations";

const sdk = new SivoIgnite();

sdk.pets.createPets().then((res: CreatePetsResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
<!-- End SDK Example Usage -->