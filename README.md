<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Analysis of Marginal Cost Volatility & Peak Events (2025)</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.6;
            margin: 40px;
            color: #222;
        }
        h1 {
            color: #0b3c5d;
            border-bottom: 2px solid #0b3c5d;
            padding-bottom: 5px;
        }
        h2 {
            color: #1f5f8b;
            margin-top: 30px;
        }
        h3 {
            color: #444;
            margin-top: 20px;
        }
        ul {
            margin-left: 20px;
        }
        li {
            margin-bottom: 8px;
        }
        .highlight {
            background-color: #f2f6fa;
            padding: 10px;
            border-left: 4px solid #1f5f8b;
            margin: 20px 0;
        }
        .tools span {
            font-weight: bold;
        }
    </style>
</head>

<body>

<h1>Analysis of Marginal Cost Volatility &amp; Peak Events (2025)</h1>

<h2>Introduction</h2>
<p>
As an <strong>Electrical Engineer transitioning into Data Analytics</strong>, I developed this project to
visualize and interpret the behavior of the <strong>Chilean electricity market</strong>.
The analysis focuses on <em>price formation</em>, <em>grid coupling</em>, and the
<em>impact of renewable energy integration</em>.
</p>

<h2>Methodology &amp; Analysis</h2>

<h3>Hourly Patterns (Heatmap Analysis)</h3>

<div class="highlight">
    <p><strong>Atacama Node</strong></p>
    <ul>
        <li>Significant hourly volatility.</li>
        <li>Low marginal costs during solar hours, often reaching <strong>0 USD/MWh</strong>.</li>
        <li>High price peaks during nocturnal ramps due to:
            <ul>
                <li>Thermal dependency</li>
                <li>Transmission limitations</li>
            </ul>
        </li>
    </ul>
</div>

<div class="highlight">
    <p><strong>Puerto Montt Node</strong></p>
    <ul>
        <li>Displays <strong>structural volatility</strong>.</li>
        <li>Unlike the Northern system, prices are frequently driven by
            <strong>local marginal technologies</strong>, mainly diesel generation.</li>
    </ul>
</div>

<h3>System Coupling &amp; Decoupling</h3>

<ul>
    <li>
        <strong>Transmission Bottlenecks:</strong>
        The analysis of the <em>“Puerto Montt Case”</em> reveals frequent
        system decoupling events, where Southern prices spike independently
        from the rest of the grid.
        This behavior highlights infrastructure <em>bottlenecks</em> preventing
        low-cost energy from the North from reaching the South.
    </li>

    <li>
        <strong>Seasonality:</strong>
        Marginal costs remain higher during the first semester
        (<strong>January–June</strong>).
        A noticeable base price reduction occurs during
        <strong>Winter and Spring (July–October)</strong>,
        driven by increased hydroelectric availability and
        high renewable penetration.
    </li>
</ul>

<h3>Peak Events</h3>

<p>
A major system-wide event was identified in <strong>March 2025</strong>,
where marginal costs surged from approximately
<strong>100 USD/MWh</strong> to nearly <strong>600 USD/MWh</strong>.
This spike is likely associated with
<strong>transmission failures</strong> or
<strong>unscheduled maintenance events</strong>.
</p>

<h2>Tools Used</h2>

<ul class="tools">
    <li><span>Python:</span> Data manipulation and cleaning.</li>
    <li><span>Matplotlib &amp; Seaborn:</span> Advanced heatmaps and multi-node time-series visualization.</li>
    <li><span>Domain Expertise:</span> Electrical market regulation and power flow theory.</li>
</ul>

</body>
</html>
