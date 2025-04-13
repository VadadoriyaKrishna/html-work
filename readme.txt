This JavaScript code creates a stacking card animation when the user scrolls. It detects when a .card-deck-js container enters the viewport using the Intersection Observer API and then applies a scroll-based transformation to the .card elements inside it. The transformation makes the cards translate and scale dynamically as the user scrolls.

- marginY(card spacing) - gap between cards
- Scaling effect  - scrolling * 0.05 to control the scaling intensity
- Card movement speed → Adjust the offsetTop or cardHeight values to change how quickly cards move.
- Trigger Animation at Different Positions → Modify the offsetTop - top calculation to start animation at a different scroll position.
