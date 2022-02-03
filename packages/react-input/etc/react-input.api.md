## API Report File for "@fluentui/react-input"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import type { IntrinsicSlotProps } from '@fluentui/react-utilities';
import * as React_2 from 'react';

// @public
export const Input: ForwardRefComponent<InputProps>;

// @public (undocumented)
export const inputClassName = "fui-Input";

// @public
export type InputOnChangeData = {
    value: string;
};

// @public (undocumented)
export type InputProps = Omit<ComponentProps<InputSlots, 'input'>, 'children' | 'defaultValue' | 'onChange' | 'size' | 'type' | 'value'> & {
    children?: never;
    size?: 'small' | 'medium' | 'large';
    inline?: boolean;
    appearance?: 'outline' | 'underline' | 'filledDarker' | 'filledLighter';
    defaultValue?: string;
    value?: string;
    onChange?: (ev: React_2.FormEvent<HTMLInputElement>, data: InputOnChangeData) => void;
    type?: 'text' | 'email' | 'password' | 'search' | 'tel' | 'url' | 'date' | 'datetime-local' | 'month' | 'number' | 'time' | 'week';
};

// @public (undocumented)
export type InputSlots = {
    root: IntrinsicSlotProps<'span'>;
    input: IntrinsicSlotProps<'input'>;
    contentBefore?: IntrinsicSlotProps<'span'>;
    contentAfter?: IntrinsicSlotProps<'span'>;
};

// @public
export type InputState = Required<Pick<InputProps, 'appearance' | 'inline' | 'size'>> & ComponentState<InputSlots>;

// @public
export const renderInput_unstable: (state: InputState) => JSX.Element;

// @public
export const useInput_unstable: (props: InputProps, ref: React_2.Ref<HTMLInputElement>) => InputState;

// @public
export const useInputStyles_unstable: (state: InputState) => InputState;

// (No @packageDocumentation comment for this package)

```