---
layout: post
title: "De kunst van het curateren van jouw consumptie"
date: 2020-09-30 11:40:31
---

<head>
    <script type="text/javascript">
        <!-- Off Day Pie Chart -->
        google.charts.setOnLoadCallback(drawOffDayChart);
        function drawOffDayChart() {
            var data = google.visualization.arrayToDataTable([
            ['Task', 'Hours per Day'],
            ['Work',     11],
            ['Eat',      2],
            ['Commute',  2],
            ['Watch TV', 2],
            ['Sleep',    7]
            ]);
            var options = {
            title: 'Mijn luie dag',
            pieHole: 0.4,
            };
            var chart = new google.visualization.PieChart(document.getElementById('mijn_luie_dag_chart'));
            chart.draw(data, options);
        }
                <!-- Mijn Project Dag Pie Chart -->
        google.charts.setOnLoadCallBack(drawMijnProjectDagChart);
        function drawMijnProjectDagChart() {
                var queryString = encodeURIComponent('');
                var data = google.visualization.Query('https://docs.google.com/spreadsheets/d/1wcQ7GrafaRaq0RgTPQVjGaK2jSZpXrKQBudcOZ-LdnQ/edit#gid=414107059&headers=9&tq=' + queryString);
                query.send(handleQueryResponse);
                var options = {
                    title: 'Mijn productievere dag',
                    pieHole: 0.4,
                };
            function handleQueryReponse(response) {
                var data = response.getDataTable();
                var chart = new google.visualization.PieChart(document.getElementById('mijn_project_dag_chart'));
                chart.draw(data, options);
            }
        }
    </script>

</head>

<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/883731430&color=%23daa520&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/goldenconvos" title="GoldenConvos BackOffice" target="_blank" style="color: #cccccc; text-decoration: none;">GoldenConvos BackOffice</a> · <a href="https://soundcloud.com/goldenconvos/waarom-je-een-blog-zou-moeten-starten" title="Waarom Je Een Blog Zou Moeten Starten" target="_blank" style="color: #cccccc; text-decoration: none;">Waarom Je Een Blog Zou Moeten Starten</a></div>

<i class="fa fa-clock-o" aria-hidden="true" style="fontsize:20px"> **20 MIN READ**</i>

**RANDY OFOSU** -- Preta is een bovennatuurlijke wezen. Het heeft een lijdensweg vele malen langer dan die van normale mens. Het ervaart een extreme vorm van onverzadigbare honger en/of dorst naar een object. Zelfs na het consumeren van dat object zal het op zoek gaan naar dat object. 

Preta heeft een hele kleine mond en dikke buik. Wat het consumeren moeilijk maakt en het hongergevoel onverdraagbaar maakt.

Deze wezen was vroeger een mens die door zijn of haar slechte karma is gestraft in hun reïncarnatiecyclus. 

*Yikes.*

> *Het moment dat je wenst naar meer, zal je nooit meer gelukkig zijn.*

Dit is een artikel over gulzigheid.

Nu heb ik een voorbeeld genomen uit het <a href="https://nl.wikipedia.org/wiki/Peta_(geest)" alt="Wikipagina: Preta de Hongerige Geest." title="Wikipagina: Preta de Hongerige Geest.">Sanskriet</a>, maar dit concept leeft in vrijwel alle religies. Dat betekend dat het vrijwel unaniem is dat gulzigheid wordt gezien als een zonde door ons allen.

We zijn niet perfect dus begaan we deze zonde nog steeds. Het nadeel van overconsumeren is dat het een negatieve invloed heeft op jouw algemene geluk en productiviteit. Als je wil presteren in het leven heb je heel wat aan dit artikel.  

Want we gaan het hebben over hoe jij jouw consumptiepatroon in toom houdt. 

## Meten = Weten
Het voordeel van jouw bezigheden tracken is dat je kan zien waar jouw tijd naartoe gaat. Maar waar het melkkoetje nou *echt* ligt is dat het je helpt behoeden op overconsumptie.

<!-- <div id="mijn_luie_dag_chart" style="width: 700px; height: 250px;"></div> -->
<div id="mijn_project_dag_chart" style="width: 700px; height: 250px;"></div>

## Weet wat je eet. (filter jouw consumptie)

