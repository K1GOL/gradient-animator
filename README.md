# Gradient Animator

Simple JS animator for CSS color gradients.

## Example usage

```html
<script type="module">
  import { gradientAnimator } from './gradientAnimator.js'

  window.onload = () => {
    gradientAnimator(document.getElementById('container'), {
      duration: 10,
      angle: { start: 130, end: 150 },
      colors: [
        {
          start: { r: 255, g: 0, b: 170},
          end: { r: 40, g: 200, b: 30 }
        },
        {
          start: { r: 255, g: 150, b: 15 },
          end: { r: 35, g: 160, b: 155}
        },
        {
          start: { r: 76, g: 255, b: 0 },
          end: { r: 220, g: 0, b: 255 }
        }
      ]
    })
  }
</script>
```