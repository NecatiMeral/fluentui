## API Report File for "@fluentui/react-slider"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import type { IntrinsicSlotProps } from '@fluentui/react-utilities';
import * as React_2 from 'react';

// @public
export const renderSlider_unstable: (state: SliderState) => JSX.Element;

// @public
export const Slider: ForwardRefComponent<SliderProps>;

// @public (undocumented)
export const sliderClassName = "fui-Slider";

// @public (undocumented)
export type SliderCommons = {
    defaultValue?: number;
    value?: number;
    min?: number;
    max?: number;
    step?: number;
    disabled?: boolean;
    vertical?: boolean;
    origin?: number;
    size?: 'small' | 'medium';
    onChange?: (ev: React_2.ChangeEvent<HTMLInputElement>, data: SliderOnChangeData) => void;
    getAriaValueText?: (value: number) => string;
};

// @public (undocumented)
export type SliderOnChangeData = {
    value: number;
};

// @public (undocumented)
export type SliderProps = Omit<ComponentProps<SliderSlots, 'input'>, 'defaultValue' | 'onChange' | 'size' | 'value'> & SliderCommons;

// @public (undocumented)
export type SliderSlots = {
    root: IntrinsicSlotProps<'div'>;
    rail: IntrinsicSlotProps<'div'>;
    thumb: IntrinsicSlotProps<'div'>;
    input: IntrinsicSlotProps<'input'> & {
        orient?: 'horizontal' | 'vertical';
    };
};

// @public (undocumented)
export type SliderState = ComponentState<SliderSlots> & SliderCommons;

// @public
export const useSlider_unstable: (props: SliderProps, ref: React_2.Ref<HTMLInputElement>) => SliderState;

// @public (undocumented)
export const useSliderState_unstable: (state: SliderState) => SliderState;

// @public
export const useSliderStyles_unstable: (state: SliderState) => SliderState;

// (No @packageDocumentation comment for this package)

```