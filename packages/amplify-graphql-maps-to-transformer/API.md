## API Report File for "@aws-amplify/graphql-maps-to-transformer"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { DirectiveNode } from 'graphql';
import { ObjectTypeDefinitionNode } from 'graphql';
import { TransformerContextProvider } from '@aws-amplify/graphql-transformer-interfaces';
import { TransformerPluginBase } from '@aws-amplify/graphql-transformer-core';
import { TransformerPreProcessContextProvider } from '@aws-amplify/graphql-transformer-interfaces';
import { TransformerSchemaVisitStepContextProvider } from '@aws-amplify/graphql-transformer-interfaces';

// @public (undocumented)
export class MapsToTransformer extends TransformerPluginBase {
    constructor();
    // (undocumented)
    after: (context: TransformerContextProvider) => void;
    // (undocumented)
    object: (definition: ObjectTypeDefinitionNode, directive: DirectiveNode, ctx: TransformerSchemaVisitStepContextProvider) => void;
    // (undocumented)
    preMutateSchema: (context: TransformerPreProcessContextProvider) => void;
}

// (No @packageDocumentation comment for this package)

```
