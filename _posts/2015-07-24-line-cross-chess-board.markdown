---
layout: post
title:  "20150724 - Line Cross Chess Board"
date:   2015-07-24 18:52:55
categories: Misc
author: ev3commander
---

#### Areteem魔法学园每日一题 2015年7月24日
<problem>
On an 8x8 chessboard, there are 64 little squares. Draw a straight line on the chessboard so that it crosses the interior of maximum number of the little squares. How many squares does the line cross?

<script>
	var marginTop = 20,
        marginLeft = 20,
        fieldSize = 30,
        boardDimension = 8,
        boardSize = boardDimension*fieldSize;

    var board =[];
    
    for(var i = 0; i < boardDimension*boardDimension; i++) {
        board.push({
            x: i % boardDimension,
            y: Math.floor(i / boardDimension),
            piece: 0
        });
    };

    var div = d3.select("problem")
        .append("div")
        .style("top", marginTop + "px")
        .style("left", marginLeft + "px")
        .style("width", boardSize + "px")
        .style("height", boardSize + "px");

    var svg = div.append("svg")
         .attr("width", boardSize + "px")
         .attr("height", boardSize + "px")
         .selectAll(".fields")
         .data(board)
        .enter()
         .append("g");

    svg.append("rect")
         .style("class", "fields")
         .style("class", "rects")
         .attr("x", function (d) {
             return d.x*fieldSize;
         })
         .attr("y", function (d) {
             return d.y*fieldSize;
         })
         .attr("width", fieldSize + "px")
         .attr("height", fieldSize + "px")
         .style("fill", function (d) {
             if ( ((d.x%2 == 0) && (d.y%2 == 0)) ||
                  ((d.x%2 == 1) && (d.y%2 == 1))    ) 
                 return "white";
             else
                 return "black";
         });
svg.append("rect").attr("x", 0).attr("y", 0).attr("width", boardSize).attr("height", boardSize).style("fill","none").style("stroke-width", "2").style("stroke","rgb(0,0,0)");
</script>
</problem>


### Solution <button>Show / Hide</button>

<solution>

<script>
	var marginTop = 20,
        marginLeft = 20,
        fieldSize = 30,
        boardDimension = 8,
        boardSize = boardDimension*fieldSize;

    var board =[];
    
    for(var i = 0; i < boardDimension*boardDimension; i++) {
        board.push({
            x: i % boardDimension,
            y: Math.floor(i / boardDimension),
            piece: 0
        });
    };

    var div = d3.select("solution")
        .append("div")
        .style("top", marginTop + "px")
        .style("left", marginLeft + "px")
        .style("width", boardSize + "px")
        .style("height", boardSize + "px");

    var svg = div.append("svg")
         .attr("width", boardSize + "px")
         .attr("height", boardSize + "px")
         .selectAll(".fields")
         .data(board)
        .enter()
         .append("g");

    svg.append("rect")
         .style("class", "fields")
         .style("class", "rects")
         .attr("x", function (d) {
             return d.x*fieldSize;
         })
         .attr("y", function (d) {
             return d.y*fieldSize;
         })
         .attr("width", fieldSize + "px")
         .attr("height", fieldSize + "px")
         .style("fill", function (d) {
             if ( ((d.x%2 == 0) && (d.y%2 == 0)) ||
                  ((d.x%2 == 1) && (d.y%2 == 1))    ) 
                 return "white";
             else
                 return "black";
         });

svg.append("rect").attr("x", 0).attr("y", 0).attr("width", boardSize).attr("height", boardSize).style("fill","none").style("stroke-width", "2").style("stroke","rgb(0,0,0)");
  
svg.append("line").attr("x1",15).attr("y1",0).attr("x2",boardSize).attr("y2",boardSize-15).style("stroke", "blue").style("stroke-width","2px");

svg.append("line").attr("x1",0).attr("y1",15).attr("x2",boardSize-15).attr("y2",boardSize).style("stroke", "red").style("stroke-width","2px");


</script>
15 squares.

</solution>

