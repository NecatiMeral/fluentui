## API Report File for "@fluentui/react-text"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import type { FunctionComponent } from 'react';
import type { IntrinsicSlotProps } from '@fluentui/react-utilities';
import * as React_2 from 'react';

// Warning: (ae-forgotten-export) The symbol "TextWrapperProps" needs to be exported by the entry point index.d.ts
//
// @public
const Body_2: FunctionComponent<TextWrapperProps>;
export { Body_2 as Body }

// @public (undocumented)
export const bodyClassName = "fui-Body";

// @public
export const Caption: FunctionComponent<TextWrapperProps>;

// @public (undocumented)
export const captionClassName = "fui-Caption";

// @public
export const Display: FunctionComponent<TextWrapperProps>;

// @public (undocumented)
export const displayClassName = "fui-Display";

// @public
export const Headline: FunctionComponent<TextWrapperProps>;

// @public (undocumented)
export const headlineClassName = "fui-Headline";

// @public
export const LargeTitle: FunctionComponent<TextWrapperProps>;

// @public (undocumented)
export const largeTitleClassName = "fui-LargeTitle";

// @public
export const renderText_unstable: (state: TextState) => JSX.Element;

// @public
export const Subheadline: FunctionComponent<TextWrapperProps>;

// @public (undocumented)
export const subheadlineClassName = "fui-Subheadline";

// @public
const Text_2: ForwardRefComponent<TextProps>;
export { Text_2 as Text }

// @public (undocumented)
export const textClassName = "fui-Text";

// @public (undocumented)
export type TextCommons = {
    wrap: boolean;
    truncate: boolean;
    block: boolean;
    italic: boolean;
    underline: boolean;
    strikethrough: boolean;
    size: 100 | 200 | 300 | 400 | 500 | 600 | 700 | 800 | 900 | 1000;
    font: 'base' | 'monospace' | 'numeric';
    weight: 'regular' | 'medium' | 'semibold';
    align: 'start' | 'center' | 'end' | 'justify';
};

// @public
export type TextProps = ComponentProps<TextSlots> & Partial<TextCommons>;

// @public
export type TextSlots = {
    root: IntrinsicSlotProps<'span', 'p' | 'h1' | 'h2' | 'h3' | 'h4' | 'h5' | 'h6' | 'pre'>;
};

// @public
export type TextState = ComponentState<TextSlots> & TextCommons;

// @public
export const Title1: FunctionComponent<TextWrapperProps>;

// @public (undocumented)
export const title1ClassName = "fui-Title1";

// @public
export const Title2: FunctionComponent<TextWrapperProps>;

// @public (undocumented)
export const title2ClassName = "fui-Title2";

// @public
export const Title3: FunctionComponent<TextWrapperProps>;

// @public (undocumented)
export const title3ClassName = "fui-Title3";

// @public
export const useText_unstable: (props: TextProps, ref: React_2.Ref<HTMLElement>) => TextState;

// @public
export const useTextStyles_unstable: (state: TextState) => TextState;

// (No @packageDocumentation comment for this package)

```