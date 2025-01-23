# Trials
<div id="box" class="jxgbox" style="width:500px; height:500px; border: 1px solid black;"></div>
<script src="https://cdn.jsdelivr.net/npm/jsxgraph/distrib/jsxgraphcore.js"></script>
<script type="text/javascript">
  var board = JXG.JSXGraph.initBoard('box', {
    boundingbox: [-5, 5, 5, -5],
    axis: true
  });
  var parabola = board.create('functiongraph', [function(x) { return x * x; }]);
</script>
