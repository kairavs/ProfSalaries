## Professor Salaries and Years Since PHD 
by Kairav Sharma 
<br>
This dataset, downloaded from [R datasets](https://vincentarelbundock.github.io/Rdatasets/articles/data.html) has information regarding professor salaries as well as background information like gender, years since PHD, years working, and even their rank. 

<br>

<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>

<div>                            <div id="2230f4d2-a20a-44bf-9fcd-ffe4046a9112" class="plotly-graph-div" style="height:100%; width:100%;"></div>            <script type="text/javascript">                                    window.PLOTLYENV=window.PLOTLYENV || {};                                    if (document.getElementById("2230f4d2-a20a-44bf-9fcd-ffe4046a9112")) {                    Plotly.newPlot(                        "2230f4d2-a20a-44bf-9fcd-ffe4046a9112",                        [{"marker": {"color": "rgb(0,30,66)", "size": 5.0}, "mode": "markers", "name": "rank=Prof", "showlegend": true, "textfont": {"color": "rgb(0,30,66)"}, "textposition": "bottom center", "type": "scatter", "x": [19, 20, 45, 40, 30, 45, 21, 18, 20, 12, 19, 38, 37, 39, 31, 36, 34, 24, 21, 35, 12, 20, 13, 22, 41, 23, 40, 38, 19, 25, 40, 23, 25, 28, 12, 16, 23, 33, 22, 35, 17, 28, 17, 45, 29, 35, 28, 17, 26, 43, 17, 22, 17, 15, 37, 25, 38, 21, 13, 30, 41, 42, 28, 16, 20, 31, 40, 20, 37, 12, 21, 30, 39, 14, 32, 24, 24, 54, 28, 32, 56, 35, 20, 16, 17, 21, 19, 27, 28, 27, 36, 14, 21, 21, 15, 26, 21, 16, 18, 25, 19, 37, 20, 28, 27, 11, 18, 26, 23, 33, 18, 25, 22, 43, 19, 34, 38, 40, 28, 17, 19, 21, 35, 18, 20, 39, 15, 26, 16, 15, 13, 21, 23, 34, 38, 20, 16, 39, 29, 38, 36, 28, 25, 46, 19, 31, 38, 23, 19, 17, 30, 21, 28, 29, 39, 20, 31, 28, 22, 32, 45, 31, 31, 37, 36, 43, 14, 47, 13, 42, 42, 12, 52, 31, 24, 46, 39, 37, 51, 45, 28, 29, 33, 32, 39, 19, 40, 18, 17, 49, 39, 27, 28, 14, 46, 33, 31, 22, 20, 14, 29, 35, 22, 46, 16, 16, 24, 24, 30, 23, 37, 23, 49, 20, 18, 33, 36, 35, 13, 32, 37, 13, 17, 38, 31, 32, 15, 41, 39, 27, 56, 38, 26, 22, 25, 49, 39, 28, 14, 23, 30, 43, 43, 15, 35, 33, 23, 12, 30, 27, 28, 38, 27, 44, 27, 15, 29, 29, 38, 33, 40, 30, 33, 31, 42, 25], "xaxis": "x", "y": [139750, 173200, 115000, 141500, 175000, 147765, 119250, 129000, 104800, 117150, 101000, 103450, 124750, 137000, 89565, 102580, 93904, 113068, 106294, 134885, 118223, 132261, 117256, 155750, 125196, 146500, 101299, 231545, 94384, 114778, 98193, 151768, 140096, 126621, 108875, 106639, 117704, 109785, 101000, 99418, 111512, 91412, 126320, 146856, 100131, 92391, 113398, 150480, 193000, 150743, 135585, 144640, 122960, 132825, 152708, 172272, 166024, 123683, 129676, 102235, 106689, 133217, 126933, 153303, 127512, 113543, 131205, 112429, 104279, 105000, 120806, 148500, 117515, 115313, 124309, 97262, 96614, 78162, 155500, 113278, 76840, 168635, 136000, 108262, 105668, 152664, 106608, 112696, 119015, 156938, 144651, 128148, 111168, 118971, 137167, 176500, 105890, 167284, 130664, 181257, 151575, 93164, 134185, 111751, 147349, 142467, 141136, 150000, 101000, 134000, 107500, 153750, 180000, 133700, 122100, 189409, 114500, 119700, 160400, 152500, 165000, 96545, 162200, 120000, 163200, 111350, 128400, 126200, 145350, 146000, 119500, 170000, 145200, 129600, 87800, 122400, 88175, 133900, 91000, 148750, 117555, 81700, 114000, 77202, 96200, 122875, 102600, 108200, 84273, 90450, 91100, 101100, 128800, 204000, 109000, 102000, 132000, 116450, 140300, 92550, 107550, 121200, 126000, 99000, 134800, 143940, 104350, 89650, 103700, 143250, 194800, 93000, 107200, 163200, 107100, 100600, 136500, 103600, 57800, 155865, 115800, 150500, 174500, 168500, 183800, 107300, 97150, 126300, 148800, 72300, 88600, 127100, 170500, 105260, 144050, 111350, 122500, 166800, 92050, 108100, 94350, 100351, 146800, 67559, 134550, 135027, 104428, 161101, 162221, 124714, 151650, 134778, 192253, 116518, 105450, 145098, 151445, 98053, 145000, 128464, 137317, 106231, 124312, 114596, 162150, 150376, 107986, 142023, 128250, 144309, 186960, 93519, 142500, 138000, 145028, 88709, 107309, 109954, 121946, 109646, 138771, 205500, 101036, 115435, 131950, 134690, 110515, 109707, 136660, 103275, 103649, 150680, 172505, 105000, 125192, 114330, 139219, 109305, 119450, 186023, 166605, 151292, 103106, 150564, 101738, 95329], "yaxis": "y"}, {"marker": {"color": "rgb(256,200,44)", "size": 5.0}, "mode": "markers", "name": "rank=AssocProf", "showlegend": true, "textfont": {"color": "rgb(0,30,66)"}, "textposition": "bottom center", "type": "scatter", "x": [6, 12, 13, 9, 23, 12, 14, 9, 10, 9, 11, 9, 9, 10, 10, 17, 18, 11, 10, 15, 19, 25, 11, 10, 10, 14, 15, 12, 12, 6, 22, 8, 17, 10, 13, 8, 13, 28, 19, 48, 9, 11, 29, 14, 13, 9, 26, 12, 30, 41, 8, 49, 11, 45, 12, 9, 13, 10, 19, 20, 10, 13, 11, 8], "xaxis": "x", "y": [97000, 119800, 74830, 100938, 93418, 103760, 83900, 90215, 100135, 90304, 103613, 100522, 107008, 105128, 105631, 95611, 83850, 82099, 82600, 81500, 82100, 62884, 83001, 77500, 73877, 100102, 81500, 103994, 113341, 95408, 98510, 101210, 105000, 95436, 100944, 100000, 103750, 106300, 86250, 90000, 113600, 118700, 105350, 109650, 107150, 70000, 73300, 83000, 74000, 88600, 88650, 81800, 104800, 70700, 71065, 95642, 126431, 99247, 104542, 81285, 108413, 78182, 104121, 86895], "yaxis": "y"}, {"marker": {"color": "rgb(0,150,207)", "size": 5.0}, "mode": "markers", "name": "rank=AsstProf", "showlegend": true, "textfont": {"color": "rgb(0,30,66)"}, "textposition": "bottom center", "type": "scatter", "x": [4, 7, 1, 2, 5, 11, 7, 4, 4, 5, 7, 1, 11, 8, 3, 4, 8, 3, 6, 6, 2, 10, 4, 3, 4, 5, 2, 4, 3, 3, 4, 4, 4, 4, 1, 2, 3, 1, 5, 3, 4, 4, 4, 7, 4, 3, 8, 7, 5, 4, 9, 4, 8, 8, 2, 8, 7, 5, 6, 8, 4, 8, 11, 4, 6, 8, 8], "xaxis": "x", "y": [79750, 79800, 77700, 78000, 82379, 77000, 79916, 80225, 80225, 77000, 86373, 70768, 74692, 75044, 75243, 68404, 73266, 86100, 84240, 88825, 88400, 97032, 84000, 72500, 72500, 73500, 72500, 73000, 72500, 89942, 92000, 95079, 92000, 92000, 88000, 89516, 89942, 88795, 91227, 92000, 92700, 92000, 92700, 91300, 91000, 63900, 69700, 63100, 69200, 77500, 73800, 73000, 74000, 78500, 85000, 74000, 74500, 74000, 84716, 84500, 80139, 83600, 78785, 74856, 77081, 75996, 81035], "yaxis": "y"}],                        {"annotations": [{"font": {"size": 16}, "showarrow": false, "text": "yrs.since.phd", "x": 0.5, "xanchor": "center", "xref": "paper", "y": 0, "yanchor": "top", "yref": "paper", "yshift": -30}], "showlegend": true, "template": {"data": {"bar": [{"error_x": {"color": "#2a3f5f"}, "error_y": {"color": "#2a3f5f"}, "marker": {"line": {"color": "#E5ECF6", "width": 0.5}}, "type": "bar"}], "barpolar": [{"marker": {"line": {"color": "#E5ECF6", "width": 0.5}}, "type": "barpolar"}], "carpet": [{"aaxis": {"endlinecolor": "#2a3f5f", "gridcolor": "white", "linecolor": "white", "minorgridcolor": "white", "startlinecolor": "#2a3f5f"}, "baxis": {"endlinecolor": "#2a3f5f", "gridcolor": "white", "linecolor": "white", "minorgridcolor": "white", "startlinecolor": "#2a3f5f"}, "type": "carpet"}], "choropleth": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "choropleth"}], "contour": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "contour"}], "contourcarpet": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "contourcarpet"}], "heatmap": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "heatmap"}], "heatmapgl": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "heatmapgl"}], "histogram": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "histogram"}], "histogram2d": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "histogram2d"}], "histogram2dcontour": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "histogram2dcontour"}], "mesh3d": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "type": "mesh3d"}], "parcoords": [{"line": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "parcoords"}], "pie": [{"automargin": true, "type": "pie"}], "scatter": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatter"}], "scatter3d": [{"line": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatter3d"}], "scattercarpet": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattercarpet"}], "scattergeo": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattergeo"}], "scattergl": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattergl"}], "scattermapbox": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scattermapbox"}], "scatterpolar": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterpolar"}], "scatterpolargl": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterpolargl"}], "scatterternary": [{"marker": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "type": "scatterternary"}], "surface": [{"colorbar": {"outlinewidth": 0, "ticks": ""}, "colorscale": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "type": "surface"}], "table": [{"cells": {"fill": {"color": "#EBF0F8"}, "line": {"color": "white"}}, "header": {"fill": {"color": "#C8D4E3"}, "line": {"color": "white"}}, "type": "table"}]}, "layout": {"annotationdefaults": {"arrowcolor": "#2a3f5f", "arrowhead": 0, "arrowwidth": 1}, "autotypenumbers": "strict", "coloraxis": {"colorbar": {"outlinewidth": 0, "ticks": ""}}, "colorscale": {"diverging": [[0, "#8e0152"], [0.1, "#c51b7d"], [0.2, "#de77ae"], [0.3, "#f1b6da"], [0.4, "#fde0ef"], [0.5, "#f7f7f7"], [0.6, "#e6f5d0"], [0.7, "#b8e186"], [0.8, "#7fbc41"], [0.9, "#4d9221"], [1, "#276419"]], "sequential": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]], "sequentialminus": [[0.0, "#0d0887"], [0.1111111111111111, "#46039f"], [0.2222222222222222, "#7201a8"], [0.3333333333333333, "#9c179e"], [0.4444444444444444, "#bd3786"], [0.5555555555555556, "#d8576b"], [0.6666666666666666, "#ed7953"], [0.7777777777777778, "#fb9f3a"], [0.8888888888888888, "#fdca26"], [1.0, "#f0f921"]]}, "colorway": ["#636efa", "#EF553B", "#00cc96", "#ab63fa", "#FFA15A", "#19d3f3", "#FF6692", "#B6E880", "#FF97FF", "#FECB52"], "font": {"color": "#2a3f5f"}, "geo": {"bgcolor": "white", "lakecolor": "white", "landcolor": "#E5ECF6", "showlakes": true, "showland": true, "subunitcolor": "white"}, "hoverlabel": {"align": "left"}, "hovermode": "closest", "mapbox": {"style": "light"}, "paper_bgcolor": "white", "plot_bgcolor": "#E5ECF6", "polar": {"angularaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "bgcolor": "#E5ECF6", "radialaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}}, "scene": {"xaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}, "yaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}, "zaxis": {"backgroundcolor": "#E5ECF6", "gridcolor": "white", "gridwidth": 2, "linecolor": "white", "showbackground": true, "ticks": "", "zerolinecolor": "white"}}, "shapedefaults": {"line": {"color": "#2a3f5f"}}, "ternary": {"aaxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "baxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}, "bgcolor": "#E5ECF6", "caxis": {"gridcolor": "white", "linecolor": "white", "ticks": ""}}, "title": {"x": 0.05}, "xaxis": {"automargin": true, "gridcolor": "white", "linecolor": "white", "ticks": "", "title": {"standoff": 15}, "zerolinecolor": "white", "zerolinewidth": 2}, "yaxis": {"automargin": true, "gridcolor": "white", "linecolor": "white", "ticks": "", "title": {"standoff": 15}, "zerolinecolor": "white", "zerolinewidth": 2}}}, "title": {"text": "Relationship between Professor Salary and Years since PHD"}, "xaxis": {"anchor": "y", "domain": [0.0, 1.0]}, "yaxis": {"anchor": "x", "domain": [0.0, 1.0], "title": {"text": "salary"}}},                        {"responsive": true}                    )                };                            </script>        </div>
<br>
The above visualization depicts the relationship between salary and years since PHD. It is quite evident that the professors who did their PHD a long time ago typically get paid more. The scatter plot also shows how the different position titles tie into both pay but also time since getting their doctorate. Assistant Professors get paid the least, and they are typically recent PHD graduates as well. 
<br>
