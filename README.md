<canvas id="canvas"></canvas>
<script src="https://unpkg.com/rive-js@0.7.6/dist/rive.min.js"></script>
<script>
  // autoplays the first animation in the default artboard
  new rive.Rive({
    src: '/practice (1).riv',
    canvas: document.getElementById('canvas'),
    autoplay: true,
    layout: new rive.Layout({fit: 'contain', alignment: 'center'}),
  })
</script>
