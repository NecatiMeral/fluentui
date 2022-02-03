## API Report File for "@fluentui/react-avatar"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentSlotProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import type { IntrinsicSlotProps } from '@fluentui/react-utilities';
import { PresenceBadge } from '@fluentui/react-badge';
import * as React_2 from 'react';
import type { SlotRenderFunction } from '@fluentui/react-utilities';

// @public (undocumented)
export const Avatar: ForwardRefComponent<AvatarProps>;

// @public (undocumented)
export const avatarClassName = "fui-Avatar";

// @public (undocumented)
export type AvatarCommons = Omit<React_2.HTMLAttributes<HTMLElement>, 'children'> & {
    name?: string;
    size: 20 | 24 | 28 | 32 | 36 | 40 | 48 | 56 | 64 | 72 | 96 | 120 | 128;
    shape: 'circular' | 'square';
    active: 'active' | 'inactive' | 'unset';
    activeAppearance: 'ring' | 'shadow' | 'ring-shadow';
    color: 'neutral' | 'brand' | 'colorful' | AvatarNamedColor;
    idForColor: string | undefined;
};

// @public
export type AvatarNamedColor = 'darkRed' | 'cranberry' | 'red' | 'pumpkin' | 'peach' | 'marigold' | 'gold' | 'brass' | 'brown' | 'forest' | 'seafoam' | 'darkGreen' | 'lightTeal' | 'teal' | 'steel' | 'blue' | 'royalBlue' | 'cornflower' | 'navy' | 'lavender' | 'purple' | 'grape' | 'lilac' | 'pink' | 'magenta' | 'plum' | 'beige' | 'mink' | 'platinum' | 'anchor';

// @public
export type AvatarProps = Omit<ComponentProps<AvatarSlots>, 'image'> & Partial<AvatarCommons> & {
    image?: Omit<IntrinsicSlotProps<'img'>, 'children'> & {
        children?: SlotRenderFunction<React_2.HTMLAttributes<HTMLImageElement>>;
    };
};

// @public (undocumented)
export type AvatarSlots = {
    root: Omit<IntrinsicSlotProps<'span'>, 'color'> & {
        children?: never;
    };
    image?: IntrinsicSlotProps<'img'>;
    initials?: IntrinsicSlotProps<'span'>;
    icon?: IntrinsicSlotProps<'span'>;
    badge?: ComponentSlotProps<typeof PresenceBadge>;
};

// @public
export type AvatarState = ComponentState<AvatarSlots> & AvatarCommons & {
    color: Exclude<AvatarCommons['color'], 'colorful'>;
};

// @public
export function getInitials(displayName: string | undefined | null, isRtl: boolean, allowPhoneInitials?: boolean): string;

// @public (undocumented)
export const renderAvatar_unstable: (state: AvatarState) => JSX.Element;

// @public (undocumented)
export const useAvatar_unstable: (props: AvatarProps, ref: React_2.Ref<HTMLElement>) => AvatarState;

// @public (undocumented)
export const useAvatarStyles_unstable: (state: AvatarState) => AvatarState;

// (No @packageDocumentation comment for this package)

```