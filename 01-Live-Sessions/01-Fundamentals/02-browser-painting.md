### Browser painting / Painting (Process) in Browser

> Read about Paint API of CSS which is different from Browser painting

#### Painting

> painting is the process of rendering pixels for each element based on their calculations,style and other info.
> It involves rendering content, backgrounds, borders and other properties.

#### Repainting

> Invalidation ->

#### DEV tool for visualise repainting

command: `cmd+shift+p`
search rendering then enable Paint flashing
or 3dots -> more tools -> rendering -> paint flashing

> Paint Flashing
> Frame rendering stats

#### Rendering

(DOM + CSSOM -> Render Tree ) + Layouting (Reflow) + painting (repainting: visual effect based on user interaction) => Rendering

Note: Painting either happen in incremental level or global level

#### Order of painting

1. BG color
2. BG images
3. border
4. children
5. other

   ![1697354665086](image/02-css-dom-painting/1697354665086.png)

#### View port units

CSS view port units: [Link](https://www.sitepoint.com/css-viewport-units-quick-start/)

web dev articles view port : [Link](https://web.dev/articles/viewport-units)

vimn = min(vw,vh)
vmax = max(vw,vh)
nvmax = n% of vmax

#### Articles

How Browser Works? [Link](https://web.dev/articles/howbrowserswork)

MDN Article for how broser work: [Link](https://medium.com/@monica1109/how-does-web-browsers-work-c95ad628a509)

Project Idea: Building Browser Engine : [Link](https://limpet.net/mbrubeck/2014/08/08/toy-layout-engine-1.html)
