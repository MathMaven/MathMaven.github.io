---
layout: post
title:  "20150922 - Reverse 2x2 Squares on Chess Board **"
date:   2015-09-22 18:52:55
categories: Misc
author: ev3commander
---

#### Areteem魔法学园每日一题 2015年9月22日
<problem>

在8x8的国际象棋盘上，定义一次操作如下：把棋盘上一个2x2的正方形黑白颠倒。能否经过若干次操作后使棋盘上恰好只有一个黑格？
On an 8x8 chessboard, define an operation as reversing all the colors of one 2x2 square. Is it possible that, after a number of operations, there is exactly a single black square remaining?

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

Coming soon.

</solution>

