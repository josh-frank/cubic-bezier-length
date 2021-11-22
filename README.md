# cubic-bezier-length

This is a demonstration in vanilla JS/HTML of an approach to measuring SVG cubic bézier path commands algebraically, without libraries like Paper or reaching into the DOM with `getTotalLength()`. Read more about this approach, which caluclates Gauss-Legendre quadratures, in the wonderful e-book *[A Primer on Bézier Curves](https://pomax.github.io/bezierinfo/#arclength)*.