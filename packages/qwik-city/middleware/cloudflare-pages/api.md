## API Report File for "@builder.io/qwik-city"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import type { Render } from '@builder.io/qwik/server';
import type { RenderOptions } from '@builder.io/qwik/server';
import type { RenderOptions as RenderOptions_2 } from '@builder.io/qwik';
import type { RequestHandler as RequestHandler_2 } from '~qwik-city-runtime';

// @alpha (undocumented)
export function createQwikCity(opts: QwikCityCloudflarePagesOptions): ({ request, next, env, waitUntil }: EventPluginContext) => Promise<Response>;

// @alpha (undocumented)
export interface EventPluginContext {
    // (undocumented)
    env: Record<string, any>;
    // (undocumented)
    next: (input?: Request | string, init?: RequestInit) => Promise<Response>;
    // (undocumented)
    request: Request;
    // (undocumented)
    waitUntil: (promise: Promise<any>) => void;
}

// @alpha @deprecated (undocumented)
export function qwikCity(render: Render, opts?: RenderOptions_2): ({ request, next, env, waitUntil }: EventPluginContext) => Promise<Response>;

// Warning: (ae-forgotten-export) The symbol "QwikCityHandlerOptions" needs to be exported by the entry point index.d.ts
//
// @alpha (undocumented)
export interface QwikCityCloudflarePagesOptions extends QwikCityHandlerOptions {
}

// @alpha (undocumented)
export type RequestHandlerCloudflarePages<T = unknown> = RequestHandler_2<T, {
    env: EventPluginContext['env'];
}>;

// (No @packageDocumentation comment for this package)

```
