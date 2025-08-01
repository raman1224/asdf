# Tailwind CSS Essential Classes Reference

## 🎨 Layout & Display

### Display
```css
block, inline-block, inline, flex, inline-flex, table, inline-table, table-caption, table-cell, table-column, table-column-group, table-footer-group, table-header-group, table-row-group, table-row, flow-root, grid, inline-grid, contents, list-item, hidden
```

### Flexbox
```css
/* Flex Container */
flex, inline-flex
flex-row, flex-row-reverse, flex-col, flex-col-reverse
flex-wrap, flex-wrap-reverse, flex-nowrap

/* Flex Items */
flex-1, flex-auto, flex-initial, flex-none
grow, grow-0, shrink, shrink-0
```

### Grid
```css
/* Grid Container */
grid, inline-grid
grid-cols-1, grid-cols-2, grid-cols-3, grid-cols-4, grid-cols-5, grid-cols-6, grid-cols-7, grid-cols-8, grid-cols-9, grid-cols-10, grid-cols-11, grid-cols-12, grid-cols-none
grid-rows-1, grid-rows-2, grid-rows-3, grid-rows-4, grid-rows-5, grid-rows-6, grid-rows-none

/* Grid Items */
col-span-1, col-span-2, col-span-3, col-span-4, col-span-5, col-span-6, col-span-7, col-span-8, col-span-9, col-span-10, col-span-11, col-span-12, col-span-full
row-span-1, row-span-2, row-span-3, row-span-4, row-span-5, row-span-6, row-span-full
col-start-1, col-start-2, col-start-3, col-start-4, col-start-5, col-start-6, col-start-7, col-start-8, col-start-9, col-start-10, col-start-11, col-start-12, col-start-13, col-start-auto
col-end-1, col-end-2, col-end-3, col-end-4, col-end-5, col-end-6, col-end-7, col-end-8, col-end-9, col-end-10, col-end-11, col-end-12, col-end-13, col-end-auto
```

## 📐 Spacing

### Padding
```css
p-0, p-px, p-0.5, p-1, p-1.5, p-2, p-2.5, p-3, p-3.5, p-4, p-5, p-6, p-7, p-8, p-9, p-10, p-11, p-12, p-14, p-16, p-20, p-24, p-28, p-32, p-36, p-40, p-44, p-48, p-52, p-56, p-60, p-64, p-72, p-80, p-96

/* Directional Padding */
pt-*, pr-*, pb-*, pl-*, px-*, py-*
```

### Margin
```css
m-0, m-px, m-0.5, m-1, m-1.5, m-2, m-2.5, m-3, m-3.5, m-4, m-5, m-6, m-7, m-8, m-9, m-10, m-11, m-12, m-14, m-16, m-20, m-24, m-28, m-32, m-36, m-40, m-44, m-48, m-52, m-56, m-60, m-64, m-72, m-80, m-96, m-auto

/* Directional Margin */
mt-*, mr-*, mb-*, ml-*, mx-*, my-*

/* Negative Margins */
-m-0, -m-px, -m-0.5, -m-1, -m-1.5, -m-2, -m-2.5, -m-3, -m-3.5, -m-4, -m-5, -m-6, -m-7, -m-8, -m-9, -m-10, -m-11, -m-12, -m-14, -m-16, -m-20, -m-24, -m-28, -m-32, -m-36, -m-40, -m-44, -m-48, -m-52, -m-56, -m-60, -m-64, -m-72, -m-80, -m-96
```

### Gap
```css
gap-0, gap-x-0, gap-y-0, gap-px, gap-x-px, gap-y-px, gap-0.5, gap-x-0.5, gap-y-0.5, gap-1, gap-x-1, gap-y-1, gap-1.5, gap-x-1.5, gap-y-1.5, gap-2, gap-x-2, gap-y-2, gap-2.5, gap-x-2.5, gap-y-2.5, gap-3, gap-x-3, gap-y-3, gap-3.5, gap-x-3.5, gap-y-3.5, gap-4, gap-x-4, gap-y-4, gap-5, gap-x-5, gap-y-5, gap-6, gap-x-6, gap-y-6, gap-7, gap-x-7, gap-y-7, gap-8, gap-x-8, gap-y-8, gap-9, gap-x-9, gap-y-9, gap-10, gap-x-10, gap-y-10, gap-11, gap-x-11, gap-y-11, gap-12, gap-x-12, gap-y-12, gap-14, gap-x-14, gap-y-14, gap-16, gap-x-16, gap-y-16, gap-20, gap-x-20, gap-y-20, gap-24, gap-x-24, gap-y-24, gap-28, gap-x-28, gap-y-28, gap-32, gap-x-32, gap-y-32, gap-36, gap-x-36, gap-y-36, gap-40, gap-x-40, gap-y-40, gap-44, gap-x-44, gap-y-44, gap-48, gap-x-48, gap-y-48, gap-52, gap-x-52, gap-y-52, gap-56, gap-x-56, gap-y-56, gap-60, gap-x-60, gap-y-60, gap-64, gap-x-64, gap-y-64, gap-72, gap-x-72, gap-y-72, gap-80, gap-x-80, gap-y-80, gap-96, gap-x-96, gap-y-96
```

## 📏 Sizing

### Width
```css
w-0, w-px, w-0.5, w-1, w-1.5, w-2, w-2.5, w-3, w-3.5, w-4, w-5, w-6, w-7, w-8, w-9, w-10, w-11, w-12, w-14, w-16, w-20, w-24, w-28, w-32, w-36, w-40, w-44, w-48, w-52, w-56, w-60, w-64, w-72, w-80, w-96, w-auto, w-1/2, w-1/3, w-2/3, w-1/4, w-2/4, w-3/4, w-1/5, w-2/5, w-3/5, w-4/5, w-1/6, w-2/6, w-3/6, w-4/6, w-5/6, w-1/12, w-2/12, w-3/12, w-4/12, w-5/12, w-6/12, w-7/12, w-8/12, w-9/12, w-10/12, w-11/12, w-full, w-screen, w-min, w-max, w-fit
```

### Height
```css
h-0, h-px, h-0.5, h-1, h-1.5, h-2, h-2.5, h-3, h-3.5, h-4, h-5, h-6, h-7, h-8, h-9, h-10, h-11, h-12, h-14, h-16, h-20, h-24, h-28, h-32, h-36, h-40, h-44, h-48, h-52, h-56, h-60, h-64, h-72, h-80, h-96, h-auto, h-1/2, h-1/3, h-2/3, h-1/4, h-2/4, h-3/4, h-1/5, h-2/5, h-3/5, h-4/5, h-1/6, h-2/6, h-3/6, h-4/6, h-5/6, h-full, h-screen, h-min, h-max, h-fit
```

### Min/Max Width & Height
```css
min-w-0, min-w-full, min-w-min, min-w-max, min-w-fit
max-w-0, max-w-none, max-w-xs, max-w-sm, max-w-md, max-w-lg, max-w-xl, max-w-2xl, max-w-3xl, max-w-4xl, max-w-5xl, max-w-6xl, max-w-7xl, max-w-full, max-w-min, max-w-max, max-w-fit, max-w-prose, max-w-screen-sm, max-w-screen-md, max-w-screen-lg, max-w-screen-xl, max-w-screen-2xl

min-h-0, min-h-full, min-h-screen, min-h-min, min-h-max, min-h-fit
max-h-0, max-h-px, max-h-0.5, max-h-1, max-h-1.5, max-h-2, max-h-2.5, max-h-3, max-h-3.5, max-h-4, max-h-5, max-h-6, max-h-7, max-h-8, max-h-9, max-h-10, max-h-11, max-h-12, max-h-14, max-h-16, max-h-20, max-h-24, max-h-28, max-h-32, max-h-36, max-h-40, max-h-44, max-h-48, max-h-52, max-h-56, max-h-60, max-h-64, max-h-72, max-h-80, max-h-96, max-h-none, max-h-full, max-h-screen, max-h-min, max-h-max, max-h-fit
```

## 🎯 Positioning

### Position
```css
static, fixed, absolute, relative, sticky
```

### Top/Right/Bottom/Left
```css
inset-0, inset-x-0, inset-y-0, inset-px, inset-x-px, inset-y-px, inset-0.5, inset-x-0.5, inset-y-0.5, inset-1, inset-x-1, inset-y-1, inset-1.5, inset-x-1.5, inset-y-1.5, inset-2, inset-x-2, inset-y-2, inset-2.5, inset-x-2.5, inset-y-2.5, inset-3, inset-x-3, inset-y-3, inset-3.5, inset-x-3.5, inset-y-3.5, inset-4, inset-x-4, inset-y-4, inset-5, inset-x-5, inset-y-5, inset-6, inset-x-6, inset-y-6, inset-7, inset-x-7, inset-y-7, inset-8, inset-x-8, inset-y-8, inset-9, inset-x-9, inset-y-9, inset-10, inset-x-10, inset-y-10, inset-11, inset-x-11, inset-y-11, inset-12, inset-x-12, inset-y-12, inset-14, inset-x-14, inset-y-14, inset-16, inset-x-16, inset-y-16, inset-20, inset-x-20, inset-y-20, inset-24, inset-x-24, inset-y-24, inset-28, inset-x-28, inset-y-28, inset-32, inset-x-32, inset-y-32, inset-36, inset-x-36, inset-y-36, inset-40, inset-x-40, inset-y-40, inset-44, inset-x-44, inset-y-44, inset-48, inset-x-48, inset-y-48, inset-52, inset-x-52, inset-y-52, inset-56, inset-x-56, inset-y-56, inset-60, inset-x-60, inset-y-60, inset-64, inset-x-64, inset-y-64, inset-72, inset-x-72, inset-y-72, inset-80, inset-x-80, inset-y-80, inset-96, inset-x-96, inset-y-96, inset-auto, inset-x-auto, inset-y-auto, inset-1/2, inset-x-1/2, inset-y-1/2, inset-1/3, inset-x-1/3, inset-y-1/3, inset-2/3, inset-x-2/3, inset-y-2/3, inset-1/4, inset-x-1/4, inset-y-1/4, inset-2/4, inset-x-2/4, inset-y-2/4, inset-3/4, inset-x-3/4, inset-y-3/4, inset-full, inset-x-full, inset-y-full

top-*, right-*, bottom-*, left-*
```

### Z-Index
```css
z-0, z-10, z-20, z-30, z-40, z-50, z-auto
```

## 🎨 Colors

### Text Colors
```css
text-inherit, text-current, text-transparent, text-black, text-white
text-slate-50, text-slate-100, text-slate-200, text-slate-300, text-slate-400, text-slate-500, text-slate-600, text-slate-700, text-slate-800, text-slate-900, text-slate-950
text-gray-50, text-gray-100, text-gray-200, text-gray-300, text-gray-400, text-gray-500, text-gray-600, text-gray-700, text-gray-800, text-gray-900, text-gray-950
text-zinc-50, text-zinc-100, text-zinc-200, text-zinc-300, text-zinc-400, text-zinc-500, text-zinc-600, text-zinc-700, text-zinc-800, text-zinc-900, text-zinc-950
text-neutral-50, text-neutral-100, text-neutral-200, text-neutral-300, text-neutral-400, text-neutral-500, text-neutral-600, text-neutral-700, text-neutral-800, text-neutral-900, text-neutral-950
text-stone-50, text-stone-100, text-stone-200, text-stone-300, text-stone-400, text-stone-500, text-stone-600, text-stone-700, text-stone-800, text-stone-900, text-stone-950
text-red-50, text-red-100, text-red-200, text-red-300, text-red-400, text-red-500, text-red-600, text-red-700, text-red-800, text-red-900, text-red-950
text-orange-50, text-orange-100, text-orange-200, text-orange-300, text-orange-400, text-orange-500, text-orange-600, text-orange-700, text-orange-800, text-orange-900, text-orange-950
text-amber-50, text-amber-100, text-amber-200, text-amber-300, text-amber-400, text-amber-500, text-amber-600, text-amber-700, text-amber-800, text-amber-900, text-amber-950
text-yellow-50, text-yellow-100, text-yellow-200, text-yellow-300, text-yellow-400, text-yellow-500, text-yellow-600, text-yellow-700, text-yellow-800, text-yellow-900, text-yellow-950
text-lime-50, text-lime-100, text-lime-200, text-lime-300, text-lime-400, text-lime-500, text-lime-600, text-lime-700, text-lime-800, text-lime-900, text-lime-950
text-green-50, text-green-100, text-green-200, text-green-300, text-green-400, text-green-500, text-green-600, text-green-700, text-green-800, text-green-900, text-green-950
text-emerald-50, text-emerald-100, text-emerald-200, text-emerald-300, text-emerald-400, text-emerald-500, text-emerald-600, text-emerald-700, text-emerald-800, text-emerald-900, text-emerald-950
text-teal-50, text-teal-100, text-teal-200, text-teal-300, text-teal-400, text-teal-500, text-teal-600, text-teal-700, text-teal-800, text-teal-900, text-teal-950
text-cyan-50, text-cyan-100, text-cyan-200, text-cyan-300, text-cyan-400, text-cyan-500, text-cyan-600, text-cyan-700, text-cyan-800, text-cyan-900, text-cyan-950
text-sky-50, text-sky-100, text-sky-200, text-sky-300, text-sky-400, text-sky-500, text-sky-600, text-sky-700, text-sky-800, text-sky-900, text-sky-950
text-blue-50, text-blue-100, text-blue-200, text-blue-300, text-blue-400, text-blue-500, text-blue-600, text-blue-700, text-blue-800, text-blue-900, text-blue-950
text-indigo-50, text-indigo-100, text-indigo-200, text-indigo-300, text-indigo-400, text-indigo-500, text-indigo-600, text-indigo-700, text-indigo-800, text-indigo-900, text-indigo-950
text-violet-50, text-violet-100, text-violet-200, text-violet-300, text-violet-400, text-violet-500, text-violet-600, text-violet-700, text-violet-800, text-violet-900, text-violet-950
text-purple-50, text-purple-100, text-purple-200, text-purple-300, text-purple-400, text-purple-500, text-purple-600, text-purple-700, text-purple-800, text-purple-900, text-purple-950
text-fuchsia-50, text-fuchsia-100, text-fuchsia-200, text-fuchsia-300, text-fuchsia-400, text-fuchsia-500, text-fuchsia-600, text-fuchsia-700, text-fuchsia-800, text-fuchsia-900, text-fuchsia-950
text-pink-50, text-pink-100, text-pink-200, text-pink-300, text-pink-400, text-pink-500, text-pink-600, text-pink-700, text-pink-800, text-pink-900, text-pink-950
text-rose-50, text-rose-100, text-rose-200, text-rose-300, text-rose-400, text-rose-500, text-rose-600, text-rose-700, text-rose-800, text-rose-900, text-rose-950
```

### Background Colors
```css
bg-inherit, bg-current, bg-transparent, bg-black, bg-white
/* Same color palette as text colors but with bg- prefix */
bg-slate-*, bg-gray-*, bg-zinc-*, bg-neutral-*, bg-stone-*, bg-red-*, bg-orange-*, bg-amber-*, bg-yellow-*, bg-lime-*, bg-green-*, bg-emerald-*, bg-teal-*, bg-cyan-*, bg-sky-*, bg-blue-*, bg-indigo-*, bg-violet-*, bg-purple-*, bg-fuchsia-*, bg-pink-*, bg-rose-*
```

### Border Colors
```css
border-inherit, border-current, border-transparent, border-black, border-white
/* Same color palette as text colors but with border- prefix */
border-slate-*, border-gray-*, border-zinc-*, border-neutral-*, border-stone-*, border-red-*, border-orange-*, border-amber-*, border-yellow-*, border-lime-*, border-green-*, border-emerald-*, border-teal-*, border-cyan-*, border-sky-*, border-blue-*, border-indigo-*, border-violet-*, border-purple-*, border-fuchsia-*, border-pink-*, border-rose-*
```

## 📝 Typography

### Font Family
```css
font-sans, font-serif, font-mono
```

### Font Size
```css
text-xs, text-sm, text-base, text-lg, text-xl, text-2xl, text-3xl, text-4xl, text-5xl, text-6xl, text-7xl, text-8xl, text-9xl
```

### Font Weight
```css
font-thin, font-extralight, font-light, font-normal, font-medium, font-semibold, font-bold, font-extrabold, font-black
```

### Line Height
```css
leading-3, leading-4, leading-5, leading-6, leading-7, leading-8, leading-9, leading-10, leading-none, leading-tight, leading-snug, leading-normal, leading-relaxed, leading-loose
```

### Text Alignment
```css
text-left, text-center, text-right, text-justify, text-start, text-end
```

### Text Transform
```css
uppercase, lowercase, capitalize, normal-case
```

### Text Decoration
```css
underline, overline, line-through, no-underline
```

### Text Overflow
```css
truncate, text-ellipsis, text-clip
```

### Vertical Alignment
```css
align-baseline, align-top, align-middle, align-bottom, align-text-top, align-text-bottom, align-sub, align-super
```

### White Space
```css
whitespace-normal, whitespace-nowrap, whitespace-pre, whitespace-pre-line, whitespace-pre-wrap, whitespace-break-spaces
```

### Word Break
```css
break-normal, break-words, break-all, break-keep
```

## 🎭 Flexbox & Grid Alignment

### Justify Content
```css
justify-normal, justify-start, justify-end, justify-center, justify-between, justify-around, justify-evenly, justify-stretch
```

### Justify Items
```css
justify-items-start, justify-items-end, justify-items-center, justify-items-stretch
```

### Justify Self
```css
justify-self-auto, justify-self-start, justify-self-end, justify-self-center, justify-self-stretch
```

### Align Content
```css
content-normal, content-center, content-start, content-end, content-between, content-around, content-evenly, content-baseline, content-stretch
```

### Align Items
```css
items-start, items-end, items-center, items-baseline, items-stretch
```

### Align Self
```css
self-auto, self-start, self-end, self-center, self-stretch, self-baseline
```

### Place Content
```css
place-content-center, place-content-start, place-content-end, place-content-between, place-content-around, place-content-evenly, place-content-baseline, place-content-stretch
```

### Place Items
```css
place-items-start, place-items-end, place-items-center, place-items-baseline, place-items-stretch
```

### Place Self
```css
place-self-auto, place-self-start, place-self-end, place-self-center, place-self-stretch
```

## 🎨 Backgrounds

### Background Size
```css
bg-auto, bg-cover, bg-contain
```

### Background Position
```css
bg-bottom, bg-center, bg-left, bg-left-bottom, bg-left-top, bg-right, bg-right-bottom, bg-right-top, bg-top
```

### Background Repeat
```css
bg-repeat, bg-no-repeat, bg-repeat-x, bg-repeat-y, bg-repeat-round, bg-repeat-space
```

### Background Attachment
```css
bg-fixed, bg-local, bg-scroll
```

### Background Clip
```css
bg-clip-border, bg-clip-padding, bg-clip-content, bg-clip-text
```

### Background Origin
```css
bg-origin-border, bg-origin-padding, bg-origin-content
```

### Gradients
```css
bg-gradient-to-t, bg-gradient-to-tr, bg-gradient-to-r, bg-gradient-to-br, bg-gradient-to-b, bg-gradient-to-bl, bg-gradient-to-l, bg-gradient-to-tl

from-inherit, from-current, from-transparent, from-black, from-white
/* Same color palette as text colors but with from- prefix */

via-inherit, via-current, via-transparent, via-black, via-white
/* Same color palette as text colors but with via- prefix */

to-inherit, to-current, to-transparent, to-black, to-white
/* Same color palette as text colors but with to- prefix */
```

## 🖼️ Borders

### Border Width
```css
border-0, border-2, border-4, border-8, border, border-x-0, border-x-2, border-x-4, border-x-8, border-x, border-y-0, border-y-2, border-y-4, border-y-8, border-y, border-s-0, border-s-2, border-s-4, border-s-8, border-s, border-e-0, border-e-2, border-e-4, border-e-8, border-e, border-t-0, border-t-2, border-t-4, border-t-8, border-t, border-r-0, border-r-2, border-r-4, border-r-8, border-r, border-b-0, border-b-2, border-b-4, border-b-8, border-b, border-l-0, border-l-2, border-l-4, border-l-8, border-l
```

### Border Style
```css
border-solid, border-dashed, border-dotted, border-double, border-hidden, border-none
```

### Border Radius
```css
rounded-none, rounded-sm, rounded, rounded-md, rounded-lg, rounded-xl, rounded-2xl, rounded-3xl, rounded-full
rounded-s-none, rounded-s-sm, rounded-s, rounded-s-md, rounded-s-lg, rounded-s-xl, rounded-s-2xl, rounded-s-3xl, rounded-s-full
rounded-e-none, rounded-e-sm, rounded-e, rounded-e-md, rounded-e-lg, rounded-e-xl, rounded-e-2xl, rounded-e-3xl, rounded-e-full
rounded-t-none, rounded-t-sm, rounded-t, rounded-t-md, rounded-t-lg, rounded-t-xl, rounded-t-2xl, rounded-t-3xl, rounded-t-full
rounded-r-none, rounded-r-sm, rounded-r, rounded-r-md, rounded-r-lg, rounded-r-xl, rounded-r-2xl, rounded-r-3xl, rounded-r-full
rounded-b-none, rounded-b-sm, rounded-b, rounded-b-md, rounded-b-lg, rounded-b-xl, rounded-b-2xl, rounded-b-3xl, rounded-b-full
rounded-l-none, rounded-l-sm, rounded-l, rounded-l-md, rounded-l-lg, rounded-l-xl, rounded-l-2xl, rounded-l-3xl, rounded-l-full
rounded-ss-none, rounded-ss-sm, rounded-ss, rounded-ss-md, rounded-ss-lg, rounded-ss-xl, rounded-ss-2xl, rounded-ss-3xl, rounded-ss-full
rounded-se-none, rounded-se-sm, rounded-se, rounded-se-md, rounded-se-lg, rounded-se-xl, rounded-se-2xl, rounded-se-3xl, rounded-se-full
rounded-ee-none, rounded-ee-sm, rounded-ee, rounded-ee-md, rounded-ee-lg, rounded-ee-xl, rounded-ee-2xl, rounded-ee-3xl, rounded-ee-full
rounded-es-none, rounded-es-sm, rounded-es, rounded-es-md, rounded-es-lg, rounded-es-xl, rounded-es-2xl, rounded-es-3xl, rounded-es-full
rounded-tl-none, rounded-tl-sm, rounded-tl, rounded-tl-md, rounded-tl-lg, rounded-tl-xl, rounded-tl-2xl, rounded-tl-3xl, rounded-tl-full
rounded-tr-none, rounded-tr-sm, rounded-tr, rounded-tr-md, rounded-tr-lg, rounded-tr-xl, rounded-tr-2xl, rounded-tr-3xl, rounded-tr-full
rounded-br-none, rounded-br-sm, rounded-br, rounded-br-md, rounded-br-lg, rounded-br-xl, rounded-br-2xl, rounded-br-3xl, rounded-br-full
rounded-bl-none, rounded-bl-sm, rounded-bl, rounded-bl-md, rounded-bl-lg, rounded-bl-xl, rounded-bl-2xl, rounded-bl-3xl, rounded-bl-full
```

## 🎭 Effects

### Box Shadow
```css
shadow-sm, shadow, shadow-md, shadow-lg, shadow-xl, shadow-2xl, shadow-inner, shadow-none
```

### Opacity
```css
opacity-0, opacity-5, opacity-10, opacity-20, opacity-25, opacity-30, opacity-40, opacity-50, opacity-60, opacity-70, opacity-75, opacity-80, opacity-90, opacity-95, opacity-100
```

### Mix Blend Mode
```css
mix-blend-normal, mix-blend-multiply, mix-blend-screen, mix-blend-overlay, mix-blend-darken, mix-blend-lighten, mix-blend-color-dodge, mix-blend-color-burn, mix-blend-hard-light, mix-blend-soft-light, mix-blend-difference, mix-blend-exclusion, mix-blend-hue, mix-blend-saturation, mix-blend-color, mix-blend-luminosity, mix-blend-plus-lighter
```

### Background Blend Mode
```css
bg-blend-normal, bg-blend-multiply, bg-blend-screen, bg-blend-overlay, bg-blend-darken, bg-blend-lighten, bg-blend-color-dodge, bg-blend-color-burn, bg-blend-hard-light, bg-blend-soft-light, bg-blend-difference, bg-blend-exclusion, bg-blend-hue, bg-blend-saturation, bg-blend-color, bg-blend-luminosity
```

## 🎪 Filters

### Blur
```css
blur-none, blur-sm, blur, blur-md, blur-lg, blur-xl, blur-2xl, blur-3xl
```

### Brightness
```css
brightness-0, brightness-50, brightness-75, brightness-90, brightness-95, brightness-100, brightness-105, brightness-110, brightness-125, brightness-150, brightness-200
```

### Contrast
```css
contrast-0, contrast-50, contrast-75, contrast-100, contrast-125, contrast-150, contrast-200
```

### Drop Shadow
```css
drop-shadow-sm, drop-shadow, drop-shadow-md, drop-shadow-lg, drop-shadow-xl, drop-shadow-2xl, drop-shadow-none
```

### Grayscale
```css
grayscale-0, grayscale
```

### Hue Rotate
```css
hue-rotate-0, hue-rotate-15, hue-rotate-30, hue-rotate-60, hue-rotate-90, hue-rotate-180
```

### Invert
```css
invert-0, invert
```

### Saturate
```css
saturate-0, saturate-50, saturate-100, saturate-150, saturate-200
```

### Sepia
```css
sepia-0, sepia
```

## 🎮 Transitions & Animations

### Transition Property
```css
transition-none, transition-all, transition, transition-colors, transition-opacity, transition-shadow, transition-transform
```

### Transition Duration
```css
duration-75, duration-100, duration-150, duration-200, duration-300, duration-500, duration-700, duration-1000
```

### Transition Timing Function
```css
ease-linear, ease-in, ease-out, ease-in-out
```

### Transition Delay
```css
delay-75, delay-100, delay-150, delay-200, delay-300, delay-500, delay-700, delay-1000
```

### Animation
```css
animate-none, animate-spin, animate-ping, animate-pulse, animate-bounce
```

## 🎯 Transforms

### Scale
```css
scale-0, scale-50, scale-75, scale-90, scale-95, scale-100, scale-105, scale-110, scale-125, scale-150
scale-x-0, scale-x-50, scale-x-75, scale-x-90, scale-x-95, scale-x-100, scale-x-105, scale-x-110, scale-x-125, scale-x-150
scale-y-0, scale-y-50, scale-y-75, scale-y-90, scale-y-95, scale-y-100, scale-y-105, scale-y-110, scale-y-125, scale-y-150
```

### Rotate
```css
rotate-0, rotate-1, rotate-2, rotate-3, rotate-6, rotate-12, rotate-45, rotate-90, rotate-180
-rotate-180, -rotate-90, -rotate-45, -rotate-12, -rotate-6, -rotate-3, -rotate-2, -rotate-1
```

### Translate
```css
translate-x-0, translate-x-px, translate-x-0.5, translate-x-1, translate-x-1.5, translate-x-2, translate-x-2.5, translate-x-3, translate-x-3.5, translate-x-4, translate-x-5, translate-x-6, translate-x-7, translate-x-8, translate-x-9, translate-x-10, translate-x-11, translate-x-12, translate-x-14, translate-x-16, translate-x-20, translate-x-24, translate-x-28, translate-x-32, translate-x-36, translate-x-40, translate-x-44, translate-x-48, translate-x-52, translate-x-56, translate-x-60, translate-x-64, translate-x-72, translate-x-80, translate-x-96, translate-x-1/2, translate-x-1/3, translate-x-2/3, translate-x-1/4, translate-x-2/4, translate-x-3/4, translate-x-full

translate-y-0, translate-y-px, translate-y-0.5, translate-y-1, translate-y-1.5, translate-y-2, translate-y-2.5, translate-y-3, translate-y-3.5, translate-y-4, translate-y-5, translate-y-6, translate-y-7, translate-y-8, translate-y-9, translate-y-10, translate-y-11, translate-y-12, translate-y-14, translate-y-16, translate-y-20, translate-y-24, translate-y-28, translate-y-32, translate-y-36, translate-y-40, translate-y-44, translate-y-48, translate-y-52, translate-y-56, translate-y-60, translate-y-64, translate-y-72, translate-y-80, translate-y-96, translate-y-1/2, translate-y-1/3, translate-y-2/3, translate-y-1/4, translate-y-2/4, translate-y-3/4, translate-y-full

/* Negative translations */
-translate-x-*, -translate-y-*
```

### Skew
```css
skew-x-0, skew-x-1, skew-x-2, skew-x-3, skew-x-6, skew-x-12
skew-y-0, skew-y-1, skew-y-2, skew-y-3, skew-y-6, skew-y-12
-skew-x-12, -skew-x-6, -skew-x-3, -skew-x-2, -skew-x-1
-skew-y-12, -skew-y-6, -skew-y-3, -skew-y-2, -skew-y-1
```

### Transform Origin
```css
origin-center, origin-top, origin-top-right, origin-right, origin-bottom-right, origin-bottom, origin-bottom-left, origin-left, origin-top-left
```

## 🎪 Interactivity

### Appearance
```css
appearance-none, appearance-auto
```

### Cursor
```css
cursor-auto, cursor-default, cursor-pointer, cursor-wait, cursor-text, cursor-move, cursor-help, cursor-not-allowed, cursor-none, cursor-context-menu, cursor-progress, cursor-cell, cursor-crosshair, cursor-vertical-text, cursor-alias, cursor-copy, cursor-no-drop, cursor-grab, cursor-grabbing, cursor-all-scroll, cursor-col-resize, cursor-row-resize, cursor-n-resize, cursor-e-resize, cursor-s-resize, cursor-w-resize, cursor-ne-resize, cursor-nw-resize, cursor-se-resize, cursor-sw-resize, cursor-ew-resize, cursor-ns-resize, cursor-nesw-resize, cursor-nwse-resize, cursor-zoom-in, cursor-zoom-out
```

### Pointer Events
```css
pointer-events-none, pointer-events-auto
```

### Resize
```css
resize-none, resize-y, resize-x, resize
```

### Scroll Behavior
```css
scroll-auto, scroll-smooth
```

### Scroll Margin
```css
scroll-m-0, scroll-m-px, scroll-m-0.5, scroll-m-1, scroll-m-1.5, scroll-m-2, scroll-m-2.5, scroll-m-3, scroll-m-3.5, scroll-m-4, scroll-m-5, scroll-m-6, scroll-m-7, scroll-m-8, scroll-m-9, scroll-m-10, scroll-m-11, scroll-m-12, scroll-m-14, scroll-m-16, scroll-m-20, scroll-m-24, scroll-m-28, scroll-m-32, scroll-m-36, scroll-m-40, scroll-m-44, scroll-m-48, scroll-m-52, scroll-m-56, scroll-m-60, scroll-m-64, scroll-m-72, scroll-m-80, scroll-m-96

/* Directional scroll margins */
scroll-mx-*, scroll-my-*, scroll-ms-*, scroll-me-*, scroll-mt-*, scroll-mr-*, scroll-mb-*, scroll-ml-*
```

### Scroll Padding
```css
scroll-p-0, scroll-p-px, scroll-p-0.5, scroll-p-1, scroll-p-1.5, scroll-p-2, scroll-p-2.5, scroll-p-3, scroll-p-3.5, scroll-p-4, scroll-p-5, scroll-p-6, scroll-p-7, scroll-p-8, scroll-p-9, scroll-p-10, scroll-p-11, scroll-p-12, scroll-p-14, scroll-p-16, scroll-p-20, scroll-p-24, scroll-p-28, scroll-p-32, scroll-p-36, scroll-p-40, scroll-p-44, scroll-p-48, scroll-p-52, scroll-p-56, scroll-p-60, scroll-p-64, scroll-p-72, scroll-p-80, scroll-p-96

/* Directional scroll padding */
scroll-px-*, scroll-py-*, scroll-ps-*, scroll-pe-*, scroll-pt-*, scroll-pr-*, scroll-pb-*, scroll-pl-*
```

### Scroll Snap
```css
scroll-snap-none, scroll-snap-x, scroll-snap-y, scroll-snap-both
snap-start, snap-end, snap-center, snap-align-none
snap-normal, snap-always
```

### Touch Action
```css
touch-auto, touch-none, touch-pan-x, touch-pan-left, touch-pan-right, touch-pan-y, touch-pan-up, touch-pan-down, touch-pinch-zoom, touch-manipulation
```

### User Select
```css
select-none, select-text, select-all, select-auto
```

### Will Change
```css
will-change-auto, will-change-scroll, will-change-contents, will-change-transform
```

## 🎨 Pseudo-Classes & States

### Hover
```css
hover:* (can be applied to any utility)
```

### Focus
```css
focus:*, focus-within:*, focus-visible:*
```

### Active & Visited
```css
active:*, visited:*
```

### Disabled & Enabled
```css
disabled:*, enabled:*
```

### Checked & Indeterminate
```css
checked:*, indeterminate:*
```

### First & Last
```css
first:*, last:*, odd:*, even:*
```

### Group States
```css
group-hover:*, group-focus:*, group-active:*
```

### Peer States
```css
peer-checked:*, peer-focus:*, peer-hover:*, peer-disabled:*
```

## 📱 Responsive Design

### Breakpoint Prefixes
```css
sm:* (min-width: 640px)
md:* (min-width: 768px)
lg:* (min-width: 1024px)
xl:* (min-width: 1280px)
2xl:* (min-width: 1536px)
```

### Dark Mode
```css
dark:* (when dark mode is active)
```

### Print
```css
print:* (when printing)
```

### Motion Preferences
```css
motion-reduce:*, motion-safe:*
```

### High Contrast
```css
contrast-more:*, contrast-less:*
```

## 🎯 Common Utility Combinations

### Centering
```css
/* Flexbox centering */
flex items-center justify-center

/* Grid centering */
grid place-items-center

/* Absolute centering */
absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2
```

### Card Component
```css
bg-white rounded-lg shadow-md p-6 border border-gray-200
```

### Button Styles
```css
/* Primary Button */
bg-blue-500 hover:bg-blue-600 text-white font-medium py-2 px-4 rounded-lg transition-colors

/* Secondary Button */
bg-gray-200 hover:bg-gray-300 text-gray-800 font-medium py-2 px-4 rounded-lg transition-colors

/* Outline Button */
border border-blue-500 text-blue-500 hover:bg-blue-500 hover:text-white font-medium py-2 px-4 rounded-lg transition-all
```

### Input Styles
```css
w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent
```

### Navigation
```css
/* Header */
bg-white shadow-sm border-b border-gray-200

/* Nav Link */
text-gray-600 hover:text-gray-900 px-3 py-2 rounded-md text-sm font-medium transition-colors
```

### Layout Containers
```css
/* Container */
max-w-7xl mx-auto px-4 sm:px-6 lg:px-8

/* Section */
py-12 sm:py-16 lg:py-20

/* Grid Layout */
grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6
```

### Loading States
```css
/* Skeleton */
animate-pulse bg-gray-200 rounded

/* Spinner */
animate-spin rounded-full border-4 border-gray-200 border-t-blue-500
```

---

## 🚀 Tips for Usage

1. **Mobile-first approach**: Start with base styles, then add responsive prefixes
2. **Combine utilities**: Mix and match for complex designs
3. **Use hover/focus states**: Enhance interactivity with state variants
4. **Dark mode support**: Add `dark:` prefixes for dark theme support
5. **Performance**: Purge unused CSS in production builds
6. **Custom values**: Use arbitrary values like `w-[123px]` when needed
7. **Group utilities**: Use `@apply` directive in CSS for reusable component styles

## 📚 Quick Reference Categories

- **Layout**: `flex`, `grid`, `block`, `hidden`
- **Spacing**: `p-*`, `m-*`, `gap-*`
- **Typography**: `text-*`, `font-*`, `leading-*`
- **Colors**: `bg-*`, `text-*`, `border-*`
- **Borders**: `border-*`, `rounded-*`
- **Effects**: `shadow-*`, `opacity-*`
- **Responsive**: `sm:*`, `md:*`, `lg:*`, `xl:*`, `2xl:*`
- **States**: `hover:*`, `focus:*`, `active:*`

This reference covers the most commonly used Tailwind CSS classes for modern web development. Keep this handy for quick reference during development!