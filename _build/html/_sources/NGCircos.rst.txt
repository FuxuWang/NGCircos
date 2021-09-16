================
1. Introduction
================

---------------
1.1 About
---------------
`NG-Circos <http://bioinfo.ibp.ac.cn/NGCircos/index.php>`__ is an interactive circular genome visualization tool to present and interpretate diverse types of genomic data based on web features.. It implements a raster-based ``SVG`` visualization using the open source Javascript framework jquery.js. NG-Circos is multiplatform and works in all major internet browsers (**Internet Explorer**, **Mozilla Firefox**, **Google Chrome**, **Safari**, **Opera**). Its speed is determined by the client’s hardware and internet browser. For smoothest user experience, we recommend **Google Chrome**.

NG-Circos can visualize popular genomic data format (such as WIG and GTF), construct various graphic elements (such as line, scatter, bubble and heatmap) and display/compare multiple genomic features, annotations and associations (such as genomic variations, expressions and gene fusions) in or between genomic intervals with 21 functional modules. NG-Circos also provides flexible interactive events and fascinating animations for each graphic element. Figures created by NG-Circos are publication-quality and downloadable.

NG-Circos provides **SNP**, **CNV**, **HEATMAP**, **LINK**, **LINE**, **SCATTER**, **ARC**, **TEXT**, **WIG**, **LOLLIPOP**, **GENE**, **CHORD**, **AUXILIARYLINE**, **BUBBLE**, **HISTGRAM**, **BACKGROUND**, **LEGEND**, **COMPARE** and **COMBINATION**, **REDIRECT**, **DOWNLOAD** totally.

.. note:: **NG-Circos itself is not a web application**, but a **visualization tool** that provides the functionality for bioinformatians to build Circos-like figure on bioinformatians' own web applications. The NG-Circos users are supposed to be familiar with HTML, CSS and JavaScript.

---------------------------
1.2 NG-Circos & Circos
---------------------------
Though NG-Circos shares its name with Circos, NG-Circos is not exactly the same as Circos desktop. **NG-Circos is a tool for programmers. It is not an app for end-users, and developers need to write code around NG-Circos to build graphcentric apps**. The comparison between NG-Circos and Circos is as follow:

.. list-table::
   :widths: 30 30 30
   :header-rows: 1

   * - Comparison 
     - NG-Circos
     - Circos
   * - Code
     - JavaScript
     - Perl
   * - Users
     - For web developers / bioinformatians
     - For end-users
   * - Interactive
     - Yes
     - No
   * - Used to
     - Build Circos-like web applications / draw figures
     - Draw figures

================
2. Demos
================

.. image:: _images/paper01.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/paper01.html

.. image:: _images/gallery01.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/gallery01.html

.. image:: _images/gallery02.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/gallery02.html

.. image:: _images/gallery03.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/gallery03.html

.. image:: _images/gallery04.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/gallery04.html

.. image:: _images/gallery05.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/gallery05.html

.. image:: _images/gallery07.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/gallery07.html

.. image:: _images/gallery08.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/gallery08.html

.. image:: _images/gallery09.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/gallery09.html

.. image:: _images/gallery10.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/gallery10.html

.. image:: _images/gallery11.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/gallery11.html

.. image:: _images/SNPAnimation01_before.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/SNPAnimation01_before.html

.. image:: _images/SNPAnimation01_after.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/SNPAnimation01_after.html

.. image:: _images/SCATTERAnimation01_after.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/SCATTERAnimation01_after.html
   
.. image:: _images/wigPlot.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/wigPlot.html
   
.. image:: _images/chord01.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/chord01.html
   
.. image:: _images/COMPARE.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/COMPARE.html
   
.. image:: _images/paper02.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/paper02.html
   
.. image:: _images/COMBINATION_SNP.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/COMBINATION_SNP.html
   
.. image:: _images/EGFR_Gene.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/EGFR_Gene.html
      
.. image:: _images/chord02.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/chord02.html
         
.. image:: _images/LOLLIPOP.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/LOLLIPOP.html

.. image:: _images/HOX.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/HOX.html
   
.. image:: _images/tp53.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/tp53.html

Tips: Click and try the demos above!

===================
3. Getting started
===================

--------------------------------
 Overview of "Getting started"
--------------------------------

.. image:: _images/view_demos_in_locale.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: demo/index.html

.. image:: _images/demo_get_started_gwas01.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/demo_get_started_gwas01.html

.. image:: _images/demo_get_started_gwas02.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/demo_get_started_gwas02.html

.. image:: _images/demo_get_started_gwas03.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/demo_get_started_gwas03.html

.. image:: _images/demo_get_started_gwas04.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/demo_get_started_gwas04.html

.. image:: _images/demo_get_started_gwas05.png
   :scale: 50%
   :alt: alternate text
   :height: 400px
   :width: 400px
   :align: left
   :target: pages/demo_get_started_gwas05.html

-----------------------------
 Step0. View demos in locale
-----------------------------
There is a very easy and quick way to experience the power of NG-Circos. **Do it step by step according to the following:**

1. Download and extract demos file `NGCircos_demos <download/NGCircos_demo.zip>`__.

2. Open **index.html** file in NGCircos_demos folder with your local browser. Yes, everything is done! You will see the following. **Click on the links**, and you can see all of our demos locally.

.. image:: _images/view_demos_in_locale.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: demo/index.html


**"NGCircos_demos"** contains three folders(**"lib"**, **"pages"**, **"data"**) and **"index.html"**. **"lib"** contains all JavaScript library files needed. **"pages"** contains configurations for demos. **"data"** contains the input data from users. The file structure of **"NGCircos_demos"**:

.. code-block:: html

   ---NGCircos_demos
      ---lib
         ---NGCircos.js
         ---d3.js
         ---jquery.js
         ---saveSvgAsPng.js
         ---svg-crowbar.js
      ---pages
         ---gallery01.html
         ---gallery02.html
         ......
      ---data
         ---Figure_ARC_DELETION.js
         ---Figure_SNP01.js
         ......
      ---index.html

--------------------------------
 Step1. Including NGCircos.js
--------------------------------
This section will familiarise you with the basic steps necessarily to start using NG-Circos. Here we will visualize the **GWAS data** in `GWAS Catalog <http://www.genome.gov/gwastudies/>`__ with NG-Circos step by step.

After Step0, you will have a **"pages"** folder in **"NGCircos_demos"** folder. Now create a new file **"gwas.html"** in **"pages"** folder, then include NGCircos.js in a <script> tag. Now, **"gwas.html"** is as follows:

.. code-block:: html

	<!DOCTYPE html>
	<html>
    	<head>
        	<meta charset="utf-8">
       		<title>NGCircos.js</title>
    	</head>
    	<body>
        	<!-- NGCircos.js, Jquery.js and D3.js import -->
        	<script src="../lib/jquery.js"></script>
        	<script src="../lib/d3.js"></script>
        	<script src="../lib/NGCircos.js"></script>
    	</body>
	</html>

.. note:: **NG-Circos** is based on **Jquery.js** and **D3.js(v3)**, so they should be included before **NGCircos.js**. **Jquery.js**, **D3.js** and **NGCircos.js** can be found in the **lib folder** of `NGCircos_demo.zip <download/NGCircos_demo.zip>`__.

--------------------------------------------------
 Step2. <div> tag to set picture position in html
--------------------------------------------------
After Step1, prepare a <div> tag with **"NG-Circos"** id to set the picture position you will draw in html. Now, **"gwas.html"** is as follows:

.. code-block:: html

	<!DOCTYPE html>
	<html>
    	<head>
        	<meta charset="utf-8">
       		<title>NGCircos.js</title>
    	</head>
    	<body>
		<!-- NGCircos.js, Jquery.js and D3.js import -->
		<script src="../lib/jquery.js"></script>
		<script src="../lib/d3.js"></script>
		<script src="../lib/NGCircos.js"></script>
		<!-- Prepare a <div> tag with "NGCircos" id to set the picture position your will draw in html -->
		<div id="NGCircos"></div>
    	</body>
	</html>

-----------------------------
 Step3. Genome configuration
-----------------------------
**"Genome configuration"** defines the number and size of chromosomes.

After Step2, We will configure **"Genome configuration"**. Genome configuration is set in a **<script>** tag. Here we configure the most used human genome - hg19, its **data tag** are defined as **NGCircosGenome**. Now, **"gwas.html"** is as follows:

.. code-block:: html

	<!DOCTYPE html>
	<html>
	    <head>
		<meta charset="utf-8">
		<title>NGCircos.js</title>
	    </head>
	    <body>
		<!-- NGCircos.js, Jquery.js and D3.js import -->
		<script src="../lib/jquery.js"></script>
		<script src="../lib/d3.js"></script>
		<script src="../lib/NGCircos.js"></script>
		<!-- Prepare a <div> tag with "NGCircos" id to set the picture position your will draw in html -->
		<div id="NGCircos"></div>
	<!-- Genome configuration -->
	<script>
	  var NGCircosGenome = [   // human hg19, data tag is NGCircosGenome
	    [ 
        ["1" , 249250621],
	     ["2" , 243199373],
	     ["3" , 198022430],
	     ["4" , 191154276],
	     ["5" , 180915260],
	     ["6" , 171115067],
	     ["7" , 159138663],
	     ["8" , 146364022],
	     ["9" , 141213431],
	     ["10" , 135534747],
	     ["11" , 135006516],
	     ["12" , 133851895],
	     ["13" , 115169878],
	     ["14" , 107349540],
	     ["15" , 102531392],
	     ["16" , 90354753],
	     ["17" , 81195210],
	     ["18" , 78077248],
	     ["19" , 59128983],
	     ["20" , 63025520],
	     ["21" , 48129895],
	     ["22" , 51304566],
	     ["X" , 155270560],
	     ["Y" , 59373566]
       ]
	  ];
	</script>
	    </body>
	</html>

.. note:: Here we configure hg19 human genome with **data tag** as **NGCircosGenome**.

-----------------------------------------------
 Step4. Initialization and Main configuration
-----------------------------------------------
**"Main configuration"** is the main configuration file of NG-Circos and mainly divided into four classes: **"Customize SVG"**, **"Customize genome"**, **"Customize Events"** and **"Customize Tooltips"**.

After Step3, We will initialize NG-Circos and configure **"Main configuration"**. Here are three changes:

1. Initialize NG-Circos

All of the **data tags** that is defined in **"Genome configuration"** and **"Data configuration"** must be initialized here. We initialize **data tag** - **NGCircosGenome** as below:

.. code-block:: javascript

	NGCircos01 = new NGCircos(NGCircosGenome,{

.. DANGER::
   All of the **data tags** that is defined in **"Genome configuration"** and **"Data configuration"** must be initialized here.

2. Main configuration

Here we configure 7 attributes in “Main configuration”, other attributes are used their default values. More attributes can be found in **"Main configuration"** part of this document.

.. list-table::
   :widths: 30 30 30 30
   :header-rows: 1

   * - Main configuration 
     - Default value
     - Class
     - Description
   * - ``target``
     - "NGCircos"
     - Customize SVG
     - SVG position in html, where <div> id is "NGCircos"
   * - ``svgWidth``
     - 900
     - Customize SVG
     - SVG width
   * - ``svgHeight``
     - 600
     - Customize SVG
     - SVG height
   * - ``svgClassName``
     - NGCircos
     - Customize genome
     - class name of SVG
   * - ``chrPad``
     - 0.04
     - Customize genome
     - distance between chromosomes
   * - ``innerRadius``
     - 246
     - Customize genome
     - inner radius of chromosome
   * - ``outerRadius``
     - 270
     - Customize genome
     - outer radius of chromosome

3. NG-Circos callback

**Callback** is necessary, Cause we add a compare module for NG-Circos, users need to call back twice, but it is usually the same, so don't need to be too concerned about it.

Now, **"gwas.html"** is as follows:

.. code-block:: html

	<!DOCTYPE html>
	<html>
	    <head>
		<meta charset="utf-8">
		<title>NGCircos.js</title>
	    </head>
	    <body>
		<!-- NGCircos.js, Jquery.js and D3.js import -->
		<script src="../lib/jquery.js"></script>
		<script src="../lib/d3.js"></script>
		<script src="../lib/NGCircos.js"></script>
		<!-- Prepare a <div> tag with "NGCircos" id to set the picture position your will draw in html -->
		<div id="NGCircos"></div>
	<!-- Genome configuration -->
	<script>
	  var NGCircosGenome = [
      [
	     ["1" , 249250621],
	     ["2" , 243199373],
	     ["3" , 198022430],
	     ["4" , 191154276],
	     ["5" , 180915260],
	     ["6" , 171115067],
	     ["7" , 159138663],
	     ["8" , 146364022],
	     ["9" , 141213431],
	     ["10" , 135534747],
	     ["11" , 135006516],
	     ["12" , 133851895],
	     ["13" , 115169878],
	     ["14" , 107349540],
	     ["15" , 102531392],
	     ["16" , 90354753],
	     ["17" , 81195210],
	     ["18" , 78077248],
	     ["19" , 59128983],
	     ["20" , 63025520],
	     ["21" , 48129895],
	     ["22" , 51304566],
	     ["X" , 155270560],
	     ["Y" , 59373566]
      ]
	  ];
	  NGCircos01 = new NGCircos(NGCircosGenome,{  // Initialize NG-Circos with "NGCircosGenome" and Main configuration
	  //Main configuration
	     target : "NGCircos",                       // Main configuration "target"
	     svgWidth : 900,                             // Main configuration "svgWidth"
	     svgHeight : 600,                            // Main configuration "svgHeight"
        svgClassName: "NGCircos",                  // Main configuration "svgClassName"
	     chrPad : 0.04,                              // Main configuration "chrPad"
	     innerRadius: 246,                           // Main configuration "innerRadius"
	     outerRadius: 270,                           // Main configuration "outerRadius"
	  });
	  NGCircos01.draw_genome(NGCircos01.genomeLength); // NG-Circos callback
     NGCircos01.draw_genome(NGCircos01.genomeLength2); // NG-Circos callback second time
	</script>
	    </body>
	</html>

Great! You have drawn a simple genome! Is it so easy? Open **"gwas.html"** file with your local browser and view it as below:

.. image:: _images/demo_get_started_gwas01.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/demo_get_started_gwas01.html

--------------------------------
 Step5. Add Data configuration
--------------------------------
**"Data configuration"** is designed for **"Function Modules"** in NG-Circos. According to **"Function Modules"** division, **"Data configuration"** includes the parts below:

.. list-table::
   :widths: 30 30 30
   :header-rows: 1

   * - Data Configuration Class
     - For Biological Data
     - Need **"Data Preparation Tools"**
   * - SNP module
     - SNP with value; GWAS data...
     - Yes
   * - SCATTER module
     - SNP without value; Genes data...
     - Yes
   * - LINK module
     - Gene fusions; Interaction; SV...
     - Yes
   * - CNV module
     - CNV with value...
     - Yes
   * - ARC module
     - CNV without value; Gene domain; Chromosome band...
     - Yes
   * - HEATMAP module
     - Gene expression...
     - Yes
   * - BUBBLE module
     - Gene expression and classification...
     - Yes
   * - HISTOGRAM module
     - Gene expression...
     - Yes
   * - LINE module
     - Gene expression...
     - Yes
   * - BACKGROUND module
     - Display background and axis circles
     - No
   * - TEXT module
     - Assigning annotation text
     - No
   * - WIG module
     - .wig file;Read depth; Gene expression...
     - Yes
   * - LOLLIPOP module
     - Muation...
     - Yes
   * - GENE module
     - Gene profile...
     - Yes
   * - CHORD module
     - Relationship between gene, exon, protein...
     - Yes
   * - REDIRECT module
     - Redirect from module to image, website...
     - No
   * - DOWNLOAD module
     - Download as SVG, PNG
     - No
   * - AUXILIARYLINE module
     - Curve, broken, straight line with 4 kinds of marker
     - No
   * - LEGEND module
     - Customize legend in circle, line, rectangle
     - No
   * - COMPARE module
     - Advanced module, display two comparable datasets in circle...
     - No
   * - COMBINATION module
     - Advanced module, display more biology details with mouse event...
     - No


We have provided **"Data Preparation Tools"** to prepare the data for almost all **"Function Modules"** except 6 auxiliary modules(**BAKCGROUND, TEXT, REDIRECT, DOWNLOAD, AUXILIARYLINE, LEGEND**, and 2 advanced modules(**COMPARE COMBINATION**),which don't require a data input.

````````````````````````````````````````````
Step5.1 Display GWAS data using SNP module
````````````````````````````````````````````

1. Input GWAS data

We download **GWAS data** from `GWAS Catalog <http://www.genome.gov/gwastudies/>`__. Then we filtered the data and just left the items which their P-value less than 1E-18. We saved the data in `SNP04_gwascatalog.txt <./data/get_started_gwas/SNP04_gwascatalog.txt>`__, as below:

.. code-block:: html

	10	100315722	20.2218	rs603424
	10	101219450	19	rs11190870
	10	103086421	25.1549	rs11191548
	10	112998590	74.0969	rs7903146
        ......
	X	5266661	24.699	rs6638512
	X	67343176	90.699	rs2497938
	X	69578860	18.1549	rs11796357
	X	79241621	32.699	rs5912838

- The first column is the name of the chromosome.
- The second column is the position of the SNP
- The third column is the value of -log10(P-value)
- The fourth column is the dbSNP id

2. Use **"Data Preparation Tools"** to prepare data

.. note:: You need to install the **python 2**, before running **NGCircos_PrepareData.py**. You can skip this step, just download `SNP04_gwascatalog.js <./data/get_started_gwas/SNP04_gwascatalog.js>`__ for the next step.

We provide a python program `NGCircos_PrepareData.py <script/NGCircos_PrepareData.py>`__ to help users prepare the input data for each module of NG-Circos

.. code-block:: shell

	python NGCircos_PrepareData.py SNP SNP04_gwascatalog.txt > SNP04_gwascatalog.js

Move `SNP04_gwascatalog.js <./data/get_started_gwas/SNP04_gwascatalog.js>`__ to ./NGCircos_demos/data/get_started_gwas/ in your local.

3. Output GWAS data used in NG-Circos



.. code-block:: javascript

	var SNP04_gwascatalog = [ "SNP04_gwascatalog" , {
	  maxRadius: 205,
	  minRadius: 153,
	  SNPFillColor: "#9400D3",
	  PointType: "circle",
	  circleSize: 2,
	  rectWidth: 2,
	  rectHeight: 2
	} , [
	  {chr: "10", pos: "100315722", value: "20.2218", des: "rs603424", color: "rgb(153,102,0)"},
	  {chr: "10", pos: "101219450", value: "19", des: "rs11190870", color: "rgb(153,102,0)"},
	  {chr: "10", pos: "103086421", value: "25.1549", des: "rs11191548", color: "rgb(153,102,0)"},
	  {chr: "10", pos: "112998590", value: "74.0969", des: "rs7903146", color: "rgb(153,102,0)"},
	  ......
	  {chr: "X", pos: "5266661", value: "24.699", des: "rs6638512", color: "rgb(153,153,153)"},
	  {chr: "X", pos: "67343176", value: "90.699", des: "rs2497938", color: "rgb(153,153,153)"},
	  {chr: "X", pos: "69578860", value: "18.1549", des: "rs11796357", color: "rgb(153,153,153)"},
	  {chr: "X", pos: "79241621", value: "32.699", des: "rs5912838", color: "rgb(153,153,153)"},
	]];

4. Including GWAS data SNP04_gwascatalog.js

Use <script> tag to include GWAS data SNP04_gwascatalog.js. And add the following code to **gwas.html**.

.. code-block:: html

	<!-- Data configuration -->
	<script src="../data/get_started_gwas/SNP04_gwascatalog.js"></script>

5. Initialize GWAS data in NG-Circos with **data tag** : **SNP04_gwascatalog**

Here GWAS data's **data tag** is defined as **SNP04_gwascatalog**. So add the following code to **gwas.html**.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(SNP04_gwascatalog,NGCircosGenome,{

Now, **"gwas.html"** is as follows:

.. code-block:: html

	<!DOCTYPE html>
	<html>
	    <head>
		<meta charset="utf-8">
		<title>NGCircos.js</title>
	    </head>
	    <body>
		<!-- NGCircos.js, Jquery.js and D3.js import -->
		<script src="../lib/jquery.js"></script>
		<script src="../lib/d3.js"></script>
		<script src="../lib/NGCircos.js"></script>
		<!-- Prepare a <div> tag with "NGCircos" id to set the picture position your will draw in html -->
		<div id="NGCircos"></div>
	<!-- Data configuration -->
	<script src="../data/get_started_gwas/SNP04_gwascatalog.js"></script>
	<!-- Genome configuration -->
	<script>
	  var NGCircosGenome = [
      [
	     ["1" , 249250621],
	     ["2" , 243199373],
	     ["3" , 198022430],
	     ["4" , 191154276],
	     ["5" , 180915260],
	     ["6" , 171115067],
	     ["7" , 159138663],
	     ["8" , 146364022],
	     ["9" , 141213431],
	     ["10" , 135534747],
	     ["11" , 135006516],
	     ["12" , 133851895],
	     ["13" , 115169878],
	     ["14" , 107349540],
	     ["15" , 102531392],
	     ["16" , 90354753],
	     ["17" , 81195210],
	     ["18" , 78077248],
	     ["19" , 59128983],
	     ["20" , 63025520],
	     ["21" , 48129895],
	     ["22" , 51304566],
	     ["X" , 155270560],
	     ["Y" , 59373566]
      ]
	  ];
	  NGCircos01 = new NGCircos(SNP04_gwascatalog,NGCircosGenome,{  // Initialize NG-Circos with "NGCircosGenome" and Main configuration
	  //Main configuration
	     target : "NGCircos",                       // Main configuration "target"
	     svgWidth : 900,                             // Main configuration "svgWidth"
	     svgHeight : 600,                            // Main configuration "svgHeight"
        svgClassName: "NGCircos",                  // Main configuration "svgClassName"
	     chrPad : 0.04,                              // Main configuration "chrPad"
	     innerRadius: 246,                           // Main configuration "innerRadius"
	     outerRadius: 270,                           // Main configuration "outerRadius"
	  });
	  NGCircos01.draw_genome(NGCircos01.genomeLength); // NG-Circos callback
     NGCircos01.draw_genome(NGCircos01.genomeLength2); // NG-Circos callback second time
	</script>
	    </body>
	</html>

Open **"gwas.html"** file with your local browser and view it as below:

.. image:: _images/demo_get_started_gwas02.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/demo_get_started_gwas02.html

````````````````````````````````````````````````````
Step5.2 Display Background using BACKGROUND module
````````````````````````````````````````````````````
1. Including BACKGROUND module configuration

BACKGROUND module's configuration is short. So we can also include BACKGROUND module as the way below.

.. note:: if your data in other module, such as SNP module, is not too much and the file is short, you can also include it as the way below.

.. code-block:: html

	<script>
	var BACKGROUND01 = [ "BACKGROUND01" , {
	  BginnerRadius: 205,
	  BgouterRadius: 153,
	  BgFillColor: "#F2F2F2",
	  BgborderColor : "#000",
	  BgborderSize : 0.3
	}];
	</script>

2. Initialize BACKGROUND module with **data tag** : **BACKGROUND01**

Here the **data tag** is defined as **BACKGROUND01**. So add the following code to **gwas.html**.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(BACKGROUND01,SNP04_gwascatalog,NGCircosGenome,{

Now, **"gwas.html"** is as follows:

.. code-block:: html

	<!DOCTYPE html>
	<html>
	    <head>
		<meta charset="utf-8">
		<title>NGCircos.js</title>
	    </head>
	    <body>
		<!-- NGCircos.js, Jquery.js and D3.js import -->
		<script src="../lib/jquery.js"></script>
		<script src="../lib/d3.js"></script>
		<script src="../lib/NGCircos.js"></script>
		<!-- Prepare a <div> tag with "NGCircos" id to set the picture position your will draw in html -->
		<div id="NGCircos"></div>
	<!-- Data configuration -->
	<script src="../data/get_started_gwas/SNP04_gwascatalog.js"></script>
	<script>
	var BACKGROUND01 = [ "BACKGROUND01" , {
	  BginnerRadius: 205,
	  BgouterRadius: 153,
	  BgFillColor: "#F2F2F2",
	  BgborderColor : "#000",
	  BgborderSize : 0.3
	}];
	</script>
	<!-- Genome configuration -->
	<script>
	  var NGCircosGenome = [
      [
	     ["1" , 249250621],
	     ["2" , 243199373],
	     ["3" , 198022430],
	     ["4" , 191154276],
	     ["5" , 180915260],
	     ["6" , 171115067],
	     ["7" , 159138663],
	     ["8" , 146364022],
	     ["9" , 141213431],
	     ["10" , 135534747],
	     ["11" , 135006516],
	     ["12" , 133851895],
	     ["13" , 115169878],
	     ["14" , 107349540],
	     ["15" , 102531392],
	     ["16" , 90354753],
	     ["17" , 81195210],
	     ["18" , 78077248],
	     ["19" , 59128983],
	     ["20" , 63025520],
	     ["21" , 48129895],
	     ["22" , 51304566],
	     ["X" , 155270560],
	     ["Y" , 59373566]
      ]
	  ];
	  NGCircos01 = new NGCircos(BACKGROUND01,SNP04_gwascatalog,NGCircosGenome,{  // Initialize NG-Circos with "NGCircosGenome" and Main configuration
	  //Main configuration
	     target : "NGCircos",                       // Main configuration "target"
	     svgWidth : 900,                             // Main configuration "svgWidth"
	     svgHeight : 600,                            // Main configuration "svgHeight"
        svgClassName: "NGCircos",                  // Main configuration "svgClassName"
	     chrPad : 0.04,                              // Main configuration "chrPad"
	     innerRadius: 246,                           // Main configuration "innerRadius"
	     outerRadius: 270,                           // Main configuration "outerRadius"
	  });
	  NGCircos01.draw_genome(NGCircos01.genomeLength); // NG-Circos callback
     NGCircos01.draw_genome(NGCircos01.genomeLength2); // NG-Circos callback second time
	</script>
	    </body>
	</html>

Open **"gwas.html"** file with your local browser and view it as below:

.. image:: _images/demo_get_started_gwas03.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/demo_get_started_gwas03.html

``````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
Step5.3 Open **MouseOver** and **MouseOut** events of SNP module in **"Main configuration"**
``````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
1. Here we configure **"Customize Events"** and **"Customize Tooltips"** two classes in **"Main configuration"** to open **MouseOver** and **MouseOut** events. More attributes can be found in **"Main configuration"** part of this document. Attributes used here are below:

.. list-table::
   :widths: 30 30 30 30
   :header-rows: 1

   * - Main configuration 
     - Value
     - Class
     - Description
   * - ``SNPMouseOverDisplay``
     - true
     - Customize Events
     - default false, [true/false], open/not open mouse mouse Over event of SNP module
   * - ``SNPMouseOverColor``
     - "red"
     - Customize Events
     - default “red”, “none” means no change, element change color after mouse Over the element
   * - ``SNPMouseOverCircleSize``
     - 5
     - Customize Events
     - default 2, “none” means no change, element change circle size after mouse Over the element
   * - ``SNPMouseOverCircleOpacity``
     - 1.0
     - Customize Events
     - default 1.0, “none” means no change, element change opacity after mouse Over the element
   * - ``SNPMouseOverCircleStrokeColor``
     - "#F26223"
     - Customize Events
     - default “#F26223”, “none” means no change, element change stroke color after mouse Over the element
   * - ``SNPMouseOverCircleStrokeWidth``
     - 3
     - Customize Events
     - default 3, “none” means no change, element change stroke width after mouse Over the element
   * - ``SNPMouseOverTooltipsSetting``
     - "style"
     - Built in styles or customize tooltips
     - default "chr : "
   * - ``SNPMouseOverTooltipsHtml``
     - " "
     - Customize Tooltips
     - default " "
   * - ``SNPMouseOverTooltipsBorderWidth``
     - 1
     - Customize Tooltips
     - default 0
   * - ``SNPMouseOutDisplay``
     - true
     - Customize Events
     - default false, [true/false], open/not open mouse mouse out event of SNP module
   * - ``SNPMouseOutAnimationTime``
     - 700
     - Customize Events
     - default 500, animation time after mouse out the element
   * - ``SNPMouseOutColor``
     - "none"
     - Customize Events
     - default “red”, “none” means no change, element change color after mouse out the element
   * - ``SNPMouseOutCircleSize``
     - "none"
     - Customize Events
     - default 2, “none” means no change, element change circle size after mouse out the element
   * - ``SNPMouseOutCircleOpacity``
     - 1.0
     - Customize Events
     - default 1.0, “none” means no change, element change opacity after mouse out the element
   * - ``SNPMouseOutCircleStrokeWidth``
     - 0
     - Customize Events
     - default 0, “none” means no change, element change stroke width after mouse out the element

.. code-block:: javascript

	  NGCircos01 = new NGCircos(BACKGROUND01,SNP04_gwascatalog,NGCircosGenome,{
	  //Main configuration
	     target : "NGCircos",
	     svgWidth : 900,
	     svgHeight : 600,
        svgClassName: "NGCircos",                
	     chrPad : 0.04,
	     innerRadius: 246,
	     outerRadius: 270,
	     SNPMouseOverDisplay : true,
	     SNPMouseOverColor : "red",
	     SNPMouseOverCircleSize : 5,
	     SNPMouseOverCircleOpacity : 1.0,
	     SNPMouseOverCircleStrokeColor : "#F26223",
	     SNPMouseOverCircleStrokeWidth : 3,
       SNPMouseOverTooltipsSetting :"style1",
	     SNPMouseOverTooltipsHtml : " ",
	     SNPMouseOverTooltipsBorderWidth : 1,
	     SNPMouseOutDisplay : true,
	     SNPMouseOutAnimationTime : 700,
	     SNPMouseOutColor : "none",
	     SNPMouseOutCircleSize : "none",
	     SNPMouseOutCircleOpacity : 1.0,
	     SNPMouseOutCircleStrokeWidth : 0,
	  });

Now, **"gwas.html"** is as follows:

.. code-block:: html

	<!DOCTYPE html>
	<html>
	    <head>
		<meta charset="utf-8">
		<title>NGCircos.js</title>
	    </head>
	    <body>
		<!-- NGCircos.js, Jquery.js and D3.js import -->
		<script src="../lib/jquery.js"></script>
		<script src="../lib/d3.js"></script>
		<script src="../lib/NGCircos.js"></script>
		<!-- Prepare a <div> tag with "NGCircos" id to set the picture position your will draw in html -->
		<div id="NGCircos"></div>
	<!-- Data configuration -->
	<script src="../data/get_started_gwas/SNP04_gwascatalog.js"></script>
	<script>
	var BACKGROUND01 = [ "BACKGROUND01" , {
	  BginnerRadius: 205,
	  BgouterRadius: 153,
	  BgFillColor: "#F2F2F2",
	  BgborderColor : "#000",
	  BgborderSize : 0.3
	}];
	</script>
	<!-- Genome configuration -->
	<script>
	  var NGCircosGenome = [
      [
	     ["1" , 249250621],
	     ["2" , 243199373],
	     ["3" , 198022430],
	     ["4" , 191154276],
	     ["5" , 180915260],
	     ["6" , 171115067],
	     ["7" , 159138663],
	     ["8" , 146364022],
	     ["9" , 141213431],
	     ["10" , 135534747],
	     ["11" , 135006516],
	     ["12" , 133851895],
	     ["13" , 115169878],
	     ["14" , 107349540],
	     ["15" , 102531392],
	     ["16" , 90354753],
	     ["17" , 81195210],
	     ["18" , 78077248],
	     ["19" , 59128983],
	     ["20" , 63025520],
	     ["21" , 48129895],
	     ["22" , 51304566],
	     ["X" , 155270560],
	     ["Y" , 59373566]
      ]
	  ];

	  NGCircos01 = new NGCircos(BACKGROUND01,SNP04_gwascatalog,NGCircosGenome,{
	  //Main configuration
	     target : "NGCircos",
	     svgWidth : 900,
	     svgHeight : 600,
        svgClassName: "NGCircos",   
	     chrPad : 0.04,
	     innerRadius: 246,
	     outerRadius: 270,
	     SNPMouseOverDisplay : true,
	     SNPMouseOverColor : "red",
	     SNPMouseOverCircleSize : 5,
	     SNPMouseOverCircleOpacity : 1.0,
	     SNPMouseOverCircleStrokeColor : "#F26223",
	     SNPMouseOverCircleStrokeWidth : 3,
	     SNPMouseOverTooltipsSetting :"style1",
       SNPMouseOverTooltipsHtml : " ",
	     SNPMouseOverTooltipsBorderWidth : 1,
	     SNPMouseOutDisplay : true,
	     SNPMouseOutAnimationTime : 700,
	     SNPMouseOutColor : "none",
	     SNPMouseOutCircleSize : "none",
	     SNPMouseOutCircleOpacity : 1.0,
	     SNPMouseOutCircleStrokeWidth : 0,
	  });
	  NGCircos01.draw_genome(NGCircos01.genomeLength);
     NGCircos01.draw_genome(NGCircos01.genomeLength2);
	</script>
	    </body>
	</html>

Open **"gwas.html"** file with your local browser and view it as below:

.. image:: _images/demo_get_started_gwas04.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/demo_get_started_gwas04.html

``````````````````````````````````````````````````````
Step5.4 Dispaly Chromosome band using ARC module
``````````````````````````````````````````````````````
**The chromosome band** represents the approximate location of bands seen on Giemsa-stained chromosomes. We have provided some commonly used genomes as below. The color of chromosome band is the same as Circos.

.. list-table::
   :widths: 15 15 15 10 20
   :header-rows: 1

   * - Species
     - Genome version
     - Data name
     - Genome
     - cytoBand in UCSC
   * - Human
     - grch38
     - ARC_grch38
     - `genome <./genome_resource/karyotype.human.grch38_genome.js>`__
     - `karyotype.human.grch38.js <./genome_resource/karyotype.human.grch38.js>`__
   * - Human
     - hg19
     - ARC_hg19
     - `genome <./genome_resource/karyotype.human.hg19_genome.js>`__
     - `karyotype.human.hg19.js <./genome_resource/karyotype.human.hg19.js>`__
   * - human
     - hg18
     - ARC_hg18
     - `genome <./genome_resource/karyotype.human.hg18_genome.js>`__
     - `karyotype.human.hg18.js <./genome_resource/karyotype.human.hg18.js>`__
   * - Mouse
     - mm10
     - ARC_mm10
     - `genome <./genome_resource/karyotype.mouse.mm10_genome.js>`__
     - `karyotype.mouse.mm10.js <./genome_resource/karyotype.mouse.mm10.js>`__
   * - Mouse
     - mm9
     - ARC_mm9
     - `genome <./genome_resource/karyotype.mouse.mm9_genome.js>`__
     - `karyotype.mouse.mm9.js <./genome_resource/karyotype.mouse.mm9.js>`__

Here we take hg19 as an example to explain how to build these files.

1. Input chromosome band data

We download chromosome band data from `UCSC <http://hgdownload.soe.ucsc.edu/goldenPath/hg19/database/>`__. Then we follow Circos's color settings on chromosome band to add the color column. We saved the data in `karyotype.human.hg19.txt <./data/karyotype.human.hg19.txt>`__, as below:


.. code-block:: html

	1	0	2300000	rgb(255,255,255)
	1	2300000	5400000	rgb(200,200,200)
	1	5400000	7200000	rgb(255,255,255)
	1	7200000	9200000	rgb(200,200,200)
	......
	Y	19800000	22100000	rgb(255,255,255)
	Y	22100000	26200000	rgb(200,200,200)
	Y	26200000	28800000	rgb(255,255,255)
	Y	28800000	59373566	rgb(220,220,220)

2. Use **"Data Preparation Tools"** to prepare data

.. note:: You need to install the **python 2**, before running **NGCircos_PrepareData.py**. You can skip this step, just download `karyotype.human.hg19.js <./data/karyotype.human.hg19.js>`__ for the next step.

We provide a python program `NGCircos_PrepareData.py <script/NGCircos_PrepareData.py>`__ to help users prepare the input data for each module of NG-Circos

.. code-block:: shell

	python NGCircos_PrepareData.py ARC karyotype.human.hg19.txt > karyotype.human.hg19.js

Move `karyotype.human.hg19.js <./data/karyotype.human.hg19.js>`__ to ./NGCircos_demos/data/ in your local.

3. Output chromosome band data used in NG-Circos

.. code-block:: javascript

	ARC_hg19 = [ "ARC_hg19" , {
	  innerRadius: -0,
	  outerRadius: -0,
	} , [
	  {chr: "1", start: "0" , end: "2300000", color: "rgb(255,255,255)"},
	  {chr: "1", start: "2300000" , end: "5400000", color: "rgb(200,200,200)"},
	  {chr: "1", start: "5400000" , end: "7200000", color: "rgb(255,255,255)"},
	  {chr: "1", start: "7200000" , end: "9200000", color: "rgb(200,200,200)"},
	  ......
	  {chr: "Y", start: "19800000" , end: "22100000", color: "rgb(255,255,255)"},
	  {chr: "Y", start: "22100000" , end: "26200000", color: "rgb(200,200,200)"},
	  {chr: "Y", start: "26200000" , end: "28800000", color: "rgb(255,255,255)"},
	  {chr: "Y", start: "28800000" , end: "59373566", color: "rgb(220,220,220)"},
	]];

4. Including chromosome band data karyotype.human.hg19.js


Use <script> tag to include chromosome band data karyotype.human.hg19.js. And add the following code to **gwas.html**.

.. code-block:: html

	<!-- Data configuration -->
	<script src="../data/get_started_gwas/karyotype.human.hg19.js"></script>

5. Initialize chromosome band data in NG-Circos with **data tag** : **ARC_hg19**

Here chromosome band data's **data tag** is defined as **ARC_hg19**. So add the following code to **gwas.html**.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(ARC_hg19,SNP04_gwascatalog,NGCircosGenome,{

Now, **"gwas.html"** is as follows:

.. code-block:: html

	<!DOCTYPE html>
	<html>
	    <head>
		<meta charset="utf-8">
		<title>NGCircos.js</title>
	    </head>
	    <body>
		<!-- NGCircos.js, Jquery.js and D3.js import -->
		<script src="../lib/jquery.js"></script>
		<script src="../lib/d3.js"></script>
		<script src="../lib/NGCircos.js"></script>
		<!-- Prepare a <div> tag with "NGCircos" id to set the picture position your will draw in html -->
		<div id="NGCircos"></div>
	<!-- Data configuration -->
	<script src="../data/karyotype.human.hg19.js"></script>
	<script src="../data/get_started_gwas/SNP04_gwascatalog.js"></script>
	<script>
	var BACKGROUND01 = [ "BACKGROUND01" , {
	  BginnerRadius: 205,
	  BgouterRadius: 153,
	  BgFillColor: "#F2F2F2",
	  BgborderColor : "#000",
	  BgborderSize : 0.3
	}];
	</script>
	<!-- Genome configuration -->
	<script>
	  var NGCircosGenome = [
      [
	     ["1" , 249250621],
	     ["2" , 243199373],
	     ["3" , 198022430],
	     ["4" , 191154276],
	     ["5" , 180915260],
	     ["6" , 171115067],
	     ["7" , 159138663],
	     ["8" , 146364022],
	     ["9" , 141213431],
	     ["10" , 135534747],
	     ["11" , 135006516],
	     ["12" , 133851895],
	     ["13" , 115169878],
	     ["14" , 107349540],
	     ["15" , 102531392],
	     ["16" , 90354753],
	     ["17" , 81195210],
	     ["18" , 78077248],
	     ["19" , 59128983],
	     ["20" , 63025520],
	     ["21" , 48129895],
	     ["22" , 51304566],
	     ["X" , 155270560],
	     ["Y" , 59373566]
      ]
	  ];

	  NGCircos01 = new NGCircos(ARC_hg19,BACKGROUND01,SNP04_gwascatalog,NGCircosGenome,{
	  //Main configuration
	     target : "NGCircos",
	     svgWidth : 900,
	     svgHeight : 600,
        svgClassName: "NGCircos",   
	     chrPad : 0.04,
	     innerRadius: 246,
	     outerRadius: 270,
	     SNPMouseOverDisplay : true,
	     SNPMouseOverColor : "red",
	     SNPMouseOverCircleSize : 5,
	     SNPMouseOverCircleOpacity : 1.0,
	     SNPMouseOverCircleStrokeColor : "#F26223",
	     SNPMouseOverCircleStrokeWidth : 3,
	     SNPMouseOverTooltipsSetting :"style1",
       SNPMouseOverTooltipsHtml : " ",
	     SNPMouseOverTooltipsBorderWidth : 1,
	     SNPMouseOutDisplay : true,
	     SNPMouseOutAnimationTime : 700,
	     SNPMouseOutColor : "none",
	     SNPMouseOutCircleSize : "none",
	     SNPMouseOutCircleOpacity : 1.0,
	     SNPMouseOutCircleStrokeWidth : 0,
	  });
	  NGCircos01.draw_genome(NGCircos01.genomeLength);
     NGCircos01.draw_genome(NGCircos01.genomeLength2); // NG-Circos callback second time
	</script>
	    </body>
	</html>

Open **"gwas.html"** file with your local browser and view it as below:

.. image:: _images/demo_get_started_gwas05.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/demo_get_started_gwas05.html


================================================
4. Function Modules and Data Preparation Tools
================================================
**"Function Modules"** are designed for specific biological data and graphic elements, which currently contains 20 modules, and later will be expanded according to the needs.

**"Data configuration"** is designed for **"Function Modules"** in NG-Circos. According to **"Function Modules"** division, **"Data configuration"** includes ten parts.

.. list-table::
   :widths: 30 30 30
   :header-rows: 1

   * - Function Modules
     - For Biological Data
     - Need **"Data Preparation Tools"**
   * - SNP module
     - SNP with value; GWAS data...
     - Yes
   * - SCATTER module
     - SNP without value; Genes data...
     - Yes
   * - LINK module
     - Gene fusions; Interaction; SV...
     - Yes
   * - CNV module
     - CNV with value...
     - Yes
   * - ARC module
     - CNV without value; Gene domain; Chromosome band...
     - Yes
   * - HEATMAP module
     - Gene expression...
     - Yes
   * - BUBBLE module
     - Gene expression and classification...
     - Yes
   * - HISTOGRAM module
     - Gene expression...
     - Yes
   * - LINE module
     - Gene expression...
     - Yes
   * - BACKGROUND module
     - Display background and axis circles
     - No
   * - TEXT module
     - Assigning annotation text
     - No
   * - WIG module
     - .wig file;Read depth; Gene expression...
     - Yes
   * - LOLLIPOP module
     - Muation...
     - Yes
   * - GENE module
     - Gene profile...
     - Yes
   * - CHORD module
     - Relationship between gene, exon, protein...
     - Yes
   * - REDIRECT module
     - Redirect from module to image, website...
     - No
   * - DOWNLOAD module
     - Download as SVG, PNG
     - No
   * - AUXILIARYLINE module
     - Curve, broken, straight line with 4 kinds of marker
     - No
   * - LEGEND module
     - Customize legend in circle, line, rectangle
     - No
   * - COMPARE module
     - Advanced module, display two comparable datasets in circle...
     - No
   * - COMBINATION module
     - Advanced module, display more biology details with mouse event...
     - No


We also have provided a python program `NGCircos_PrepareData.py <script/NGCircos_PrepareData.py>`__ as **"Data Preparation Tools"** to prepare the input data for almost all **"Function Modules"** except **6 auxiliary modules(**BAKCGROUND, TEXT, REDIRECT, DOWNLOAD, AUXILIARYLINE, LEGEND, **and 2 advanced modules(**COMPARE COMBINATION**). Below will use this tool to introduce how to prepare the data for each module.

------------------------------
4.1 Data Preparation Tools
------------------------------

``````````````````````````````````````````````````````
(1) NGCircos_PrepareData.py
``````````````````````````````````````````````````````
We provide a python program `NGCircos_PrepareData.py <script/NGCircos_PrepareData.py>`__ to help users prepare the input data for each module of NG-Circos.

.. note:: If you are familiar with a script language such as Python, Perl, Shell, you can also convert the data format by yourself. Data format is defined in **"6. API: Data configuration"**.

You need to install Python 2* before running NGCircos_PrepareData.py. The usage of NGCircos_PrepareData.py is as below:

.. code-block:: python

	Python Version: Python 2.7.3

	Usage:
	
	python NGCircos_PrepareData.py <module: SNP|SCATTER|LINK|CNV|ARC|HEATMAP|HISTOGRAM|LINE|WIG|LOLLIPOP|GENE|CHORD|COMBINATION_SNP> <input: input.txt>  >  <output:output.js>
	
	Arguments:
	
	module: Specify the module name of NG-Circos, including SNP,SCATTER,LINK,CNV,ARC,HEATMAP,HISTOGRAM,LINE,WIG,LOLLIPOP,GENE,CHORD and COMBINATION_SNP
	input : input data input.txt 
	output: output data output.js
	
	Example:

	python NGCircos_PrepareData.py SNP SNP01.txt > SNP01.js

.. note:: If you open the COMBINATION event, you may need to select the specific module, like COMBINATION_SNP. Since the graph for COMBINATION is highly customizable, this python script may not work if you change the column number of the graph, which originally is 5 in COMBINATION_SNP01.txt.

``````````````````````````````````````````````````````
(2) NGCircos_LocusZoomData.py
``````````````````````````````````````````````````````
We provide a python program `NGCircos_LocusZoomData.py <script/NGCircos_LocusZoomData.py>`__ to help users prepare the LocusZoom data for NG-Circos automatically.

.. note:: If you are familiar with a script language such as Python, Perl, Shell, you can also convert the data format by yourself. Data format is defined in **"6. API: Data configuration"**.

You need to install Python 2* before running NGCircos_LocusZoomData.py. The usage of NGCircos_LocusZoomData.py is as below:

.. code-block:: python

  Python Version: Python 2.7.3

  Usage:
  
  python NGCircos_LocusZoomData.py <--snp> <--out> <--bfile> <--ld-snp> <--ld-window-kb> <--ld-window> <--ld-window-r2> <--recombRate> <--gene_annotation>
  
  Arguments:
  
  --snp: The file address of SNP file, each row with such structure: <chromosome position p-value chr:pos ....>. First 4 columns are required!
  --out: The output address of output file(postfix with .js)
  --bfile: The ped file address, same parameter as plink
  --ld-snp: SNP(chr:pos),same parameter as plink
  --ld-window-kb: ,default b200, same parameter as plink
  --ld-window: default 99999, same parameter as plink
  --ld-window-r2: 0, same parameter as plink
  --recombRate: The file address for hapmap data which store the recombination rate of each SNP
  --gene_annotation: The file address for gene annotation data from gencode

  We apply a `project package <script/NGCircos_LocusZoom.zip>` here including a shell script, by executing which with a given SNP(chr:pos), a javascript file for circos-locusZoom plot will be generated automatically.

.. code-block:: shell

  Usage:
  ./run.sh chr:pos

  Example:
  ./run.sh chr10:94097048

  The output .js file will be stored at result/chr_pos 

-------------------
4.2 SNP module
-------------------
**"SNP module"** is used to display the **SNP density data**, **GWAS data**, etc. Of course, other data have similar structure can also be displayed by SNP module.

.. note:: We will use four steps to illustrate the input data preparation and how to use SNP module, below is an example.

        - Input data: `SNP01.txt <./data/data_prepare/SNP01.txt>`__
        - Input data used in NG-Circos: `SNP01.js <./data/data_prepare/SNP01.js>`__

``````````````````````````````````````````````````````
(1) SNP data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

	#chr	pos	value	des
	10	100315722	20.2218	rs603424
	10	101219450	19	rs11190870
	10	103086421	25.1549	rs11191548
	10	112998590	74.0969	rs7903146
	 ......
	X	5266661	24.699	rs6638512
	X	67343176	90.699	rs2497938
	X	69578860	18.1549	rs11796357
	X	79241621	32.699	rs5912838

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``pos``) is the position of the SNP.
- The 3 column(``value``) is the value(density, P-value, etc.) of the SNP.
- The 4 column(``des``) is the description of the SNP.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"SNP01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

	python NGCircos_PrepareData.py SNP SNP01.txt > SNP01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, such as ``minRadius``, and finally SNP01.js is in the following:

.. code-block:: javascript

	var SNP01 = [ "SNP01" , {
	  maxRadius: 205,
	  minRadius: 153,
	  SNPFillColor: "#9400D3",
	  PointType: "circle",
	  circleSize: 2,
	  rectWidth: 2,
	  rectHeight: 2
	} , [
	  {chr: "10", pos: "100315722", value: "20.2218", des: "rs603424", color: "rgb(153,102,0)"},
	  {chr: "10", pos: "101219450", value: "19", des: "rs11190870", color: "rgb(153,102,0)"},
	  {chr: "10", pos: "103086421", value: "25.1549", des: "rs11191548", color: "rgb(153,102,0)"},
	  {chr: "10", pos: "112998590", value: "74.0969", des: "rs7903146", color: "rgb(153,102,0)"},
	  {chr: "10", pos: "121577821", value: "169.699", des: "rs2981579", color: "rgb(153,102,0)"},
	   ......
	  {chr: "X", pos: "5266661", value: "24.699", des: "rs6638512", color: "rgb(153,153,153)"},
	  {chr: "X", pos: "67343176", value: "90.699", des: "rs2497938", color: "rgb(153,153,153)"},
	  {chr: "X", pos: "69578860", value: "18.1549", des: "rs11796357", color: "rgb(153,153,153)"},
	  {chr: "X", pos: "79241621", value: "32.699", des: "rs5912838", color: "rgb(153,153,153)"},
	]];

``````````````````````````````````````````````````````
(2) Including SNP data
``````````````````````````````````````````````````````

Use <script> tag to include SNP01.js.

.. code-block:: html

	<script src="../data/data_prepare/SNP01.js"></script>

``````````````````````````````````````````````````````
(3) Initialize SNP data with **data tag** : **SNP01**
``````````````````````````````````````````````````````

Here the data's **data tag** is defined as **SNP01**.

.. code-block:: javascript

	NGCircos01 = new NGCircos(SNP01,NGCircosGenome,{  // Initialize with "SNP01" data tag

``````````````````````````````````````````````````````
(4) Visualization of SNP module using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_SNP_Module.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_SNP_Module.html

-------------------
4.3 SCATTER module
-------------------
**"SCATTER module"** is used to display the **SNP without value**, **Genes data**, etc. Of course, other data have similar structure can also be displayed by SCATTER module.

.. note:: We will use four steps to illustrate the input data preparation and how to use SCATTER module, below is an example.

        - Input data: `SCATTER01.txt <./data/data_prepare/SCATTER01.txt>`__
        - Input data used in NG-Circos: `SCATTER01.js <./data/data_prepare/SCATTER01.js>`__

``````````````````````````````````````````````````````
(1) SCATTER data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

	#chr    start   end     name    des
	1	1102484	1102578	hsa-mir-200b	breast cancer
	11	122017230	122017301	hsa-let-7a-2	ovarian cancer
	22	46508629	46508702	hsa-let-7a-3	leukemia cancer
	14	101349316	101349412	hsa-mir-127	breast cancer

Five fields are required:

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``start``) is the start position of the scatter.
- The 3 column(``end``) is the end position of the scatter.
- The 4 column(``name``) is the name of the scatter.
- The 5 column(``des``) is the description of the scatter.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"SCATTER01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

	python NGCircos_PrepareData.py SCATTER SCATTER01.txt > SCATTER01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally SCATTER01.js is in the following:

.. code-block:: javascript

	var SCATTER01 = [ "SCATTER01" , {
	  SCATTERRadius: 220,
	  innerCircleSize: 1,
	  outerCircleSize: 7,
	  innerCircleColor: "red",
	  outerCircleColor: "#CC3399",
	  innerPointType: "circle", //circle,rect
	  outerPointType: "circle", //circle,rect
	  innerrectWidth: 2,
	  innerrectHeight: 2,
	  outerrectWidth: 10,
	  outerrectHeight: 10,
	  outerCircleOpacity: 1,
	  random_data: 0
	} , [
	  {chr: "1", start: "1102484", end: "1102578", name: "hsa-mir-200b", des: "breast cancer"},
	  {chr: "11", start: "122017230", end: "122017301", name: "hsa-let-7a-2", des: "ovarian cancer"},
	  {chr: "22", start: "46508629", end: "46508702", name: "hsa-let-7a-3", des: "leukemia cancer"},
	  {chr: "14", start: "101349316", end: "101349412", name: "hsa-mir-127", des: "breast cancer"},
	]];

``````````````````````````````````````````````````````
(2) Including SCATTER data
``````````````````````````````````````````````````````

Use <script> tag to include SCATTER01.js.

.. code-block:: html

	<script src="../data/data_prepare/SCATTER01.js"></script>

``````````````````````````````````````````````````````````````````````````````````````
(3) Initialize SCATTER data with **data tag** : **SCATTER01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **SCATTER01**.

.. code-block:: javascript

	NGCircos01 = new NGCircos(SCATTER01,NGCircosGenome,{     // Initialize with "SCATTER01" data tag

``````````````````````````````````````````````````````````````````````````````````````
(4) Visualization of SCATTER data using NG-Circos
``````````````````````````````````````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_SCATTER_Module.png
   :scale: 50%
   :alt: alternate text
   :align: center
   :target: pages/DataPreparationTools_SCATTER_Module.html

-------------------
4.4 LINK module
-------------------
**"LINK module"** is used to display the **Gene fusions data**, **Interaction data**, **"SV data"** etc. Of course, other data have similar structure can also be displayed by LINK module.

.. note:: We will use four steps to illustrate the input data preparation and how to use LINK module, below is an example.

        - Input data: `LINK01.txt <./data/data_prepare/LINK01.txt>`__
        - Input data used in NG-Circos: `LINK01.js <./data/data_prepare/LINK01.js>`__

``````````````````````````````````````````````````````
(1) LINK data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

	#name	g1chr	g1start	g1end	g1name	g2chr	g2start	g2end	g2name
	FGFR3--TACC3	4	1795662	1808986	FGFR3	4	1723217	1746905	TACC3
	CCDC6--RET	10	43595894	43623714	RET	10	61552678	61666182	TACC3
	ETV6--NTRK3	12	11905384	12043977	ETV6	15	88420169	88799384	NTRK3
	EGFR--SEPT14	7	55086971	55273307	EGFR	7	55861237	55930482	SEPT14
	EML4--ALK	2	42472644	42557344	EML4	2	29416093	30143525	ALK
	ABL1--BCR	9	133589707	133761067	ABL1	22	23523148	23657706	BCR

Nine fields are required:

- The 1 column(``name``) is the name of the link.
- The 2 column(``g1chr``) is the chromosome of gene 1.
- The 3 column(``g1start``) is the start of gene 1.
- The 4 column(``g1end``) is the end of gene 1.
- The 5 column(``g1name``) is the name of gene 1.
- The 6 column(``g2chr``) is the chromosome of gene 2.
- The 7 column(``g2start``) is the start of gene 2.
- The 8 column(``g2end``) is the end of gene 2.
- The 9 column(``g2name``) is the name of gene 2.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"LINK01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

	python NGCircos_PrepareData.py LINK LINK01.txt > LINK01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally LINK01.js is in the following:

.. code-block:: javascript

	var LINK01 = [ "LINK01" , {
	  LinkRadius: 140,
	  LinkFillColor: "#F26223",
	  LinkWidth: 3,
     LinkType:"Q",
	  displayLinkAxis: true,
	  LinkAxisColor: "#B8B8B8",
	  LinkAxisWidth: 0.5,
	  LinkAxisPad: 3,
	  displayLinkLabel: true,
	  LinkLabelColor: "red",
	  LinkLabelSize: 13,
	  LinkLabelPad: 8,
	} , [
	  {fusion: "FGFR3--TACC3", g1chr: "4", g1start: "1795662", g1end: "1808986", g1name: "FGFR3", g2chr: "4", g2start: "1723217", g2end: "1746905", g2name: "TACC3"},
	  {fusion: "CCDC6--RET", g1chr: "10", g1start: "43595894", g1end: "43623714", g1name: "RET", g2chr: "10", g2start: "61552678", g2end: "61666182", g2name: "TACC3"},
	  {fusion: "ETV6--NTRK3", g1chr: "12", g1start: "11905384", g1end: "12043977", g1name: "ETV6", g2chr: "15", g2start: "88420169", g2end: "88799384", g2name: "NTRK3"},
	  {fusion: "EGFR--SEPT14", g1chr: "7", g1start: "55086971", g1end: "55273307", g1name: "EGFR", g2chr: "7", g2start: "55861237", g2end: "55930482", g2name: "SEPT14"},
	  {fusion: "EML4--ALK", g1chr: "2", g1start: "42472644", g1end: "42557344", g1name: "EML4", g2chr: "2", g2start: "29416093", g2end: "30143525", g2name: "ALK"},
	  {fusion: "ABL1--BCR", g1chr: "9", g1start: "133589707", g1end: "133761067", g1name: "ABL1", g2chr: "22", g2start: "23523148", g2end: "23657706", g2name: "BCR"},
	]];

``````````````````````````````````````````````````````
(2) Including LINK data
``````````````````````````````````````````````````````

Use <script> tag to include LINK01.js.

.. code-block:: html

	<script src="../data/LINK01.js"></script>

``````````````````````````````````````````````````````
(3) Initialize NG-Circos with LINK data
``````````````````````````````````````````````````````

Prepare a <div> tag with **"example"** id to set the picture position your will draw in html, e.g.:

.. code-block:: javascript

	NGCircos01 = new NGCircos(LINK01,NGCircosGenome,{ // Initialize with "LINK01" data tag

``````````````````````````````````````````````````````
(4) Visualization of LINK data using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_LINK_Module.png
   :scale: 50%
   :alt: alternate text
   :align: center
   :target: pages/DataPreparationTools_LINK_Module.html

-------------------
4.5 CNV module
-------------------
**"CNV module"** is used to display the **CNV data**, etc. Of course, other data have similar structure can also be displayed by CNV module.

.. note:: We will use four steps to illustrate the input data preparation and how to use CNV module, below is an example.

        - Input data: `CNV01.txt <./data/data_prepare/CNV01.txt>`__
        - Input data used in NG-Circos: `CNV01.js <./data/data_prepare/CNV01.js>`__

``````````````````````````````````````````````````````
(1) CNV data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

	#chr	start	end	value
	1	764788	87109267	2.5
	1	87109268	120217058	2
	1	144101324	222713034	4
	1	222713035	222867750	6
	......
	9	30330084	140139368	3.5
	X	105073	114046817	1
	X	114112404	114299959	2
	X	114376344	154884814	1

Four fields are required:

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``start``) is the start of the CNV region.
- The 3 column(``end``) is the end of the CNV region.
- The 4 column(``value``) is the copy number of CNV region.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"CNV01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

	python NGCircos_PrepareData.py CNV CNV01.txt > CNV01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally CNV01.js is in the following:

.. code-block:: javascript

	var CNV01 = [ "CNV01" , {
	  maxRadius: 175,
	  minRadius: 116,
	  CNVwidth: 2,
	  CNVColor: "#4876FF",
	} , [
	  {chr: "1", start: "764788", end: "87109267", value: "2.5"},
	  {chr: "1", start: "87109268", end: "120217058", value: "2"},
	  {chr: "1", start: "144101324", end: "222713034", value: "4"},
	  {chr: "1", start: "222713035", end: "222867750", value: "6"},
	  ......
	  {chr: "9", start: "30330084", end: "140139368", value: "3.5"},
	  {chr: "X", start: "105073", end: "114046817", value: "1"},
	  {chr: "X", start: "114112404", end: "114299959", value: "2"},
	  {chr: "X", start: "114376344", end: "154884814", value: "1"},
	]];

``````````````````````````````````````````````````````
(2) Including CNV data
``````````````````````````````````````````````````````

Use <script> tag to include CNV01.js.

.. code-block:: html

	<script src="../data/data_prepare/CNV01.js"></script>

``````````````````````````````````````````````````````
(3) Initialize CNV data with **data tag** : **CNV01**
``````````````````````````````````````````````````````

Here the data's **data tag** is defined as **CNV01**.

.. code-block:: javascript

	NGCircos01 = new NGCircos(BACKGROUND01,CNV01,NGCircosGenome,{  // Initialize with "CNV01" data tag

``````````````````````````````````````````````````````
(4) Visualization of CNV data using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_CNV_Module.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_CNV_Module.html

-------------------
4.6 ARC module
-------------------
**"ARC module"** is used to display the **CNV without value**, **Gene domain**, **Chromosome band**, etc. Of course, other data have similar structure can also be displayed by ARC module.

.. note:: We will use four steps to illustrate the input data preparation and how to use ARC module, below is an example.

        - Input data: `ARC01.txt <./data/data_prepare/ARC01.txt>`__
        - Input data used in NG-Circos: `ARC01.js <./data/data_prepare/ARC01.js>`__

``````````````````````````````````````````````````````
(1) ARC data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

	#chr	start	end	color	des
	EGFR	57	167	#CD8500	Recep_L domain
	EGFR	185	338	blue	Furin-like domain
	EGFR	361	480	#CD8500	Recep_L domain
	EGFR	505	636	yellow	GF_recep_IV domain
	EGFR	713	965	red	Pkinase Tyr domain

Five fields are required:

- The 1 column(``chr``) is the name of the chromosome. In this example, this field specify the protein name.
- The 2 column(``start``) is the start of the arc.
- The 3 column(``end``) is the end of the arc.
- The 4 column(``color``) is the color of the arc.
- The 5 column(``des``) is the description of the arc.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"ARC01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

	python NGCircos_PrepareData.py ARC ARC01.txt > ARC01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally ARC01.js is in the following:

.. code-block:: javascript

	var ARC01 = [ "ARC01" , {
	  innerRadius: -55,
	  outerRadius: -45,
	} , [
	  {chr: "EGFR", start: "57", end: "167", color: "#CD8500", des: "Recep_L domain"},
	  {chr: "EGFR", start: "185", end: "338", color: "blue", des: "Furin-like domain"},
	  {chr: "EGFR", start: "361", end: "480", color: "#CD8500", des: "Recep_L domain"},
	  {chr: "EGFR", start: "505", end: "636", color: "yellow", des: "GF_recep_IV domain"},
	  {chr: "EGFR", start: "713", end: "965", color: "red", des: "Pkinase Tyr domain"},
	]];

``````````````````````````````````````````````````````
(2) Including ARC data
``````````````````````````````````````````````````````

Use <script> tag to include ARC01.js.

.. code-block:: html

	<script src="../data/data_prepare/ARC01.js"></script>

``````````````````````````````````````````````````````
(3) Initialize ARC data with **data tag** : **ARC01**
``````````````````````````````````````````````````````

Here the data's **data tag** is defined as **ARC01**.

.. code-block:: javascript

	NGCircos01 = new NGCircos(TEXT01,ARC01,NGCircosGenome,{   // Initialize with "ARC01" data tag


``````````````````````````````````````````````````````
(4) Visualization of ARC module using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_ARC_Module.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_ARC_Module.html

-------------------
4.7 HEATMAP module
-------------------
**"HEATMAP module"** is used to display the **Gene expression data**, etc. Of course, other data have similar structure can also be displayed by HEATMAP module.

.. note:: We will use four steps to illustrate the input data preparation and how to use HEATMAP module, below is an example.

        - Input data: `HEATMAP01.txt <./data/data_prepare/HEATMAP01.txt>`__
        - Input data used in NG-Circos: `HEATMAP01.js <./data/data_prepare/HEATMAP01.js>`__

``````````````````````````````````````````````````````
(1) HEATMAP data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

	#chr	start	end	name	value
	2L	1	1011544	test heatmap	0.8
	2L	1011548	2011544	test heatmap	0.3
	2L	2011548	3011544	test heatmap	0.1
	2L	2011545	2011546	test heatmap	0.01
	......
	X	18011548	19011544	test heatmap	0.83
	X	19011548	20011544	test heatmap	0.39
	X	20011548	21146708	test heatmap	0.49
	X	21011548	22422827	test heatmap	0.83

Five fields are required:

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``start``) is the start of the region.
- The 3 column(``end``) is the end of the region.
- The 4 column(``name``) is the name of the region.
- The 5 column(``value``) is the value of the region.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"HEATMAP01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

	python NGCircos_PrepareData.py HEATMAP HEATMAP01.txt > HEATMAP01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally HEATMAP01.js is in the following:

.. code-block:: javascript

	var HEATMAP01 = [ "HEATMAP01" , {
	  innerRadius: -25,
	  outerRadius: -65,
	  maxColor: "red",
	  minColor: "yellow"
	} , [
	  {chr: "2L", start: "1", end: "1011544", name: "test heatmap", value: "0.8"},
	  {chr: "2L", start: "1011548", end: "2011544", name: "test heatmap", value: "0.3"},
	  {chr: "2L", start: "2011548", end: "3011544", name: "test heatmap", value: "0.1"},
	  {chr: "2L", start: "2011545", end: "2011546", name: "test heatmap", value: "0.01"},
	......
	  {chr: "X", start: "18011548", end: "19011544", name: "test heatmap", value: "0.83"},
	  {chr: "X", start: "19011548", end: "20011544", name: "test heatmap", value: "0.39"},
	  {chr: "X", start: "20011548", end: "21146708", name: "test heatmap", value: "0.49"},
	  {chr: "X", start: "21011548", end: "22422827", name: "test heatmap", value: "0.83"},
	]];

``````````````````````````````````````````````````````
(2) Including HEATMAP data
``````````````````````````````````````````````````````

Use <script> tag to include HEATMAP01.js.

.. code-block:: html

	<script src="../data/data_prepare/HEATMAP01.js"></script>

``````````````````````````````````````````````````````````````````````````````````````
(3) Initialize HEATMAP data with **data tag** : **HEATMAP01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **HEATMAP01**.

.. code-block:: javascript

	NGCircos01 = new NGCircos(HEATMAP01,NGCircosGenome,{ // Initialize with "HEATMAP01" data tag

``````````````````````````````````````````````````````
(4) Visualization of HEATMAP data using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_HEATMAP_Module.png
   :scale: 50%
   :alt: alternate text
   :align: center
   :target: pages/DataPreparationTools_HEATMAP_Module.html

---------------------
4.8 HISTOGRAM module
---------------------
**"HISTOGRAM module"** is used to display the **Gene expression data**, etc. Of course, other data have similar structure can also be displayed by HISTOGRAM module.

.. note:: We will use four steps to illustrate the input data preparation and how to use HISTOGRAM module, below is an example.

        - Input data: `HISTOGRAM01.txt <./data/data_prepare/HISTOGRAM01.txt>`__
        - Input data used in NGCircos: `HISTOGRAM01.js <./data/data_prepare/HISTOGRAM01.js>`__


``````````````````````````````````````````````````````
(1) HISTOGRAM data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

	#chr	start	end	name	value
	2L	1	1011544	test histogram	0.8
	2L	1011548	2011544	test histogram	0.3
	2L	2011548	3011544	test histogram	0.1
	2L	2011545	2011546	test histogram	0.01
	......
	X	18011548	19011544	test histogram	0.83
	X	19011548	20011544	test histogram	0.39
	X	20011548	21146708	test histogram	0.49
	X	21011548	22422827	test histogram	0.83

Five fields are required:

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``start``) is the start of the region.
- The 3 column(``end``) is the end of the region.
- The 4 column(``name``) is the name of the region.
- The 5 column(``value``) is the value of the region.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"HISTOGRAM01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

	python NGCircos_PrepareData.py HISTOGRAM HISTOGRAM01.txt > HISTOGRAM01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally HISTOGRAM01.js is in the following:

.. code-block:: javascript

	var HISTOGRAM01 = [ "HISTOGRAM01" , {
	  maxRadius: 220,
	  minRadius: 185,
	  histogramFillColor: "#FF6666",
	} , [
	  {chr: "2L", start: "1", end: "1011544", name: "test histogram", value: "0.8"},
	  {chr: "2L", start: "1011548", end: "2011544", name: "test histogram", value: "0.3"},
	  {chr: "2L", start: "2011548", end: "3011544", name: "test histogram", value: "0.1"},
	  {chr: "2L", start: "2011545", end: "2011546", name: "test histogram", value: "0.01"},
	  ......
	  {chr: "X", start: "18011548", end: "19011544", name: "test histogram", value: "0.83"},
	  {chr: "X", start: "19011548", end: "20011544", name: "test histogram", value: "0.39"},
	  {chr: "X", start: "20011548", end: "21146708", name: "test histogram", value: "0.49"},
	  {chr: "X", start: "21011548", end: "22422827", name: "test histogram", value: "0.83"},
	]];

``````````````````````````````````````````````````````
(2) Including HISTOGRAM data
``````````````````````````````````````````````````````

Use <script> tag to include HISTOGRAM01.js.

.. code-block:: html

	<script src="../data/data_prepare/HISTOGRAM01.js"></script>

``````````````````````````````````````````````````````````````````````````````````````
(3) Initialize HISTOGRAM data with **data tag** : **HISTOGRAM01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **HISTOGRAM01**.

.. code-block:: javascript

	NGCircos01 = new NGCircos(HISTOGRAM01,NGCircosGenome,{ // Initialize with "HISTOGRAM01" data tag

``````````````````````````````````````````````````````````````````````````````````````
(4) Visualization of HISTOGRAM data using NG-Circos
``````````````````````````````````````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_HISTOGRAM_Module.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_HISTOGRAM_Module.html

-------------------
4.9 LINE module
-------------------
**"LINE module"** is used to display the **Gene expression data**, etc. Of course, other data have similar structure can also be displayed by LINE module.

.. note:: We will use four steps to illustrate the input data preparation and how to use LINE module, below is an example.

        - Input data: `LINE01.txt <./data/data_prepare/LINE01.txt>`__
        - Input data used in NG-Circos: `LINE01.js <./data/data_prepare/LINE01.js>`__

``````````````````````````````````````````````````````
(1) LINE data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

	#chr	pos	value
	1	813468	0.5
	1	3383745	0.22385
	1	6157646	0.238643
	1	24793116	0.876947
	......
	X	136860114	0.267261
	X	138413104	0.847613
	X	149344414	0.830811
	X	154203563	0.43466

Three fields are required:

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``pos``) is the position of the point.
- The 3 column(``value``) is the value of the point.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"LINE01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

	python NGCircos_PrepareData.py LINE LINE01.txt > LINE01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally LINE01.js is in the following:

.. code-block:: javascript

	var LINE01 = [ "LINE01" , {
	  maxRadius: 220,
	  minRadius: 170,
	  LineColor: "#EEAD0E",
	  LineWidth: 2,
	} , [
	  {chr: "1", pos: "813468", value: "0.5"},
	  {chr: "1", pos: "3383745", value: "0.22385"},
	  {chr: "1", pos: "6157646", value: "0.238643"},
	  {chr: "1", pos: "24793116", value: "0.876947"},
	  ......
	  {chr: "X", pos: "136860114", value: "0.267261"},
	  {chr: "X", pos: "138413104", value: "0.847613"},
	  {chr: "X", pos: "149344414", value: "0.830811"},
	  {chr: "X", pos: "154203563", value: "0.43466"},
	]];

``````````````````````````````````````````````````````
(2) Including LINE data
``````````````````````````````````````````````````````

Use <script> tag to include LINE01.js.

.. code-block:: html

	<script src="../data/data_prepare/LINE01.js"></script>

``````````````````````````````````````````````````````````````````````````````````````
(3) Initialize LINE data with **data tag** : **LINE01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **LINE01**.

.. code-block:: javascript

	NGCircos01 = new NGCircos(BACKGROUND01,LINE01,NGCircosGenome,{ // Initialize with "LINE01" data tag

``````````````````````````````````````````````````````
(4) Visualization of LINE data using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_LINE_Module.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_LINE_Module.html

-----------------------
4.10 BACKGROUND module
-----------------------
**"BACKGROUND module"** is used to display background and axis circles for other modules.

.. note:: **"BACKGROUND module"** has no data entry, only the configuration parameters. We will illustrate how to use BACKGROUND module, below is an example.

``````````````````````````````````````````````````````
(1) Including BACKGROUND configuration
``````````````````````````````````````````````````````

Use <script> tag to include BACKGROUND01, BACKGROUND02, BACKGROUND03.

.. code-block:: html

	<!-- Data configuration -->
	<script>
	var BACKGROUND01 = [ "BACKGROUND01" , {
	  BginnerRadius: 230,
	  BgouterRadius: 200,
	  BgFillColor: "#F2F2F2",
	  BgborderColor : "#000",
	  BgborderSize : 0.3,
	  axisShow: "true",
	  axisWidth: 0.1,
	  axisColor: "#000",
	  axisNum: 8
	}];
	var BACKGROUND02 = [ "BACKGROUND02" , {
	  BginnerRadius: 170,
	  BgouterRadius: 130,
	  BgFillColor: "#F2F2F2",
	  BgborderColor : "#000",
	  BgborderSize : 0.3,
	  axisShow: "true",
	  axisWidth: 0.1,
	  axisColor: "#000",
	  axisNum: 8
	}];
	var BACKGROUND03 = [ "BACKGROUND03" , {
	  BginnerRadius: 100,
	  BgouterRadius: 50,
	  BgFillColor: "#F2F2F2",
	  BgborderColor : "#000",
	  BgborderSize : 0.3,
	  axisShow: "false",
	  axisWidth: 0.1,
	  axisColor: "#000",
	  axisNum: 8
	}];
	</script>

``````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
(2) Initialize BACKGROUND configuration with **data tag** : **BACKGROUND01**, **BACKGROUND02**, **BACKGROUND03**
``````````````````````````````````````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **BACKGROUND01**, **BACKGROUND02** and **BACKGROUND03**.

.. code-block:: javascript

	NGCircos01 = new NGCircos(BACKGROUND01,BACKGROUND02,BACKGROUND03,NGCircosGenome,{  // Initialize with data tag

``````````````````````````````````````````````````````````````````````````````````````
(3) Visualization of BACKGROUND module using NG-Circos
``````````````````````````````````````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_BACKGROUND_Module.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_BACKGROUND_Module.html

-------------------
4.11 TEXT module
-------------------
**"TEXT module"** is used to display annotation text at specific elements.

.. note:: **"TEXT module"** has no data entry, only the configuration parameters. We will illustrate how to use TEXT module, below is an example.

``````````````````````````````````````````````````````
(1) Including TEXT configuration
``````````````````````````````````````````````````````

Use <script> tag to include TEXT01.

.. code-block:: html

	<!-- Data configuration -->
	<script>
	  var TEXT01 = [ "TEXT01" , {
	     x: -20,
	     y: 0,
	     textSize: 20,
	     textWeight: "bold",
	     textColor: "red",
	     textOpacity: 1.0,
	     text: "EGFR"
	  }];
	</script>

``````````````````````````````````````````````````````````````````````````````````````
(2) Initialize TEXT configuration with **data tag** : **TEXT01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **TEXT01**.

.. code-block:: javascript

	NGCircos01 = new NGCircos(TEXT01,NGCircosGenome,{  // Initialize with "TEXT01" data tag

``````````````````````````````````````````````````````
(3) Visualization of TEXT module using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_TEXT_Module.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_TEXT_Module.html

-------------------
4.12 WIG module
-------------------
**"WIG module"** is used to display the **Gene expression** data, etc. Of course, other data have similar structure can also be displayed by WIG module.

.. note:: We will use four steps to illustrate the input data preparation and how to use WIG module, below is an example.

        - Input data: `WIG01.txt <./data/data_prepare/WIG01.txt>`__
        - Input data used in NG-Circos: `WIG01.js <./data/data_prepare/WIG01.js>`__

``````````````````````````````````````````````````````
(1) WIG data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

   #chr	posStart   posEnd	value
   1	813468   813470	6
   1	3383745   3383747	3
   1	6157646   6157648	3
   1	24793116   24793118	9
   ......
   X	136860114   136860116	3
   X	138413104   138413106	9
   X	149344414   149344416	9
   X	154203563   154203565	5

Three fields are required:

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``posStart``) is the start position of the sequence.
- The 3 column(``posEnd``) is the end position of the sequence.
- The 4 column(``value``) is the value of the point.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"WIG01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

   python NGCircos_PrepareData.py WIG WIG01.txt > WIG01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally WIG01.js is in the following:

.. code-block:: javascript

   var WIG01 = [ "WIG01" , {
     maxRadius: 220,
     minRadius: 170,
     WIGStrokeColor: "#EEAD0E",
     WIGColor: "red",
     WIGWIGStrokeType: "cardinal",
   } , [
     {chr: "1", pos: "813468", value: "6"},
     {chr: "1", pos: "813469", value: "6"},
     {chr: "1", pos: "813470", value: "6"},
     {chr: "1", pos: "3383745", value: "3"},
     ......
     {chr: "X", pos: "136860114", value: "3"},
     {chr: "X", pos: "136860115", value: "3"},
     {chr: "X", pos: "136860116", value: "3"},
     {chr: "X", pos: "138413104", value: "9"},
   ]];

``````````````````````````````````````````````````````
(2) Including WIG data
``````````````````````````````````````````````````````

Use <script> tag to include WIG01.js.

.. code-block:: html

   <script src="../data/data_prepare/WIG01.js"></script>

``````````````````````````````````````````````````````````````````````````````````````
(3) Initialize WIG data with **data tag** : **WIG01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **WIG01**.

.. code-block:: javascript

   NGCircos01 = new NGCircos(BACKGROUND01,WIG01,NGCircosGenome,{ // Initialize with "WIG01" data tag

``````````````````````````````````````````````````````
(4) Visualization of WIG data using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_WIG_Module.png
   :scale: 20%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_WIG_Module.html

----------------------
4.13 LOLLIPOP module
----------------------
**"LOLLIPOP module"** is used to display the **Mutation** data, etc. Of course, other data have similar structure can also be displayed by LOLLIPOP module.

.. note:: We will use four steps to illustrate the input data preparation and how to use LOLLIPOP module, below is an example.

         - Input data: `LOLLIPOP01.txt <./data/data_prepare/LOLLIPOP01.txt>`__
         - Input data used in NG-Circos: `LOLLIPOP01.js <./data/data_prepare/LOLLIPOP01.js>`__

``````````````````````````````````````````````````````
(1) LOLLIPOP data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

   #protein   chr   pos   strand   CancerTypeNumber   AA_pos   AA_change   Consequence   color   type   link
   EGFR	7	101219410	+	2	AA_858	L/R	missense_variant	#FEFF00	Hetero	https://www.intogen.org/search?gene=EGFR
   EGFR	7	101219417	+	2	AA_858	L/R	missense_variant	#FEFF00	Homo	https://www.intogen.org/search?gene=EGFR
   EGFR	7	101219425	+	1	AA_858	L/R	missense_variant	#FEFF00	Homo	https://www.intogen.org/search?gene=EGFR
   EGFR	7	101219431	+	3	AA_858	L/R	missense_variant	#FEFF00	Homo	https://www.intogen.org/search?gene=EGFR
   ......
   EGFR	7	101220278	+	3	AA_858	L/R	missense_variant	#FEFF00	Hetero	https://www.intogen.org/search?gene=EGFR
   EGFR	7	101220281	+	2	AA_858	L/R	missense_variant	#FEFF00	Homo	https://www.intogen.org/search?gene=EGFR
   EGFR	7	101220288	+	1	AA_858	L/R	missense_variant	#FEFF00	Homo	https://www.intogen.org/search?gene=EGFR
   EGFR	7	101220295	+	1	AA_858	L/R	missense_variant	#FEFF00	Hetero	https://www.intogen.org/search?gene=EGFR

Three fields are required:

- The 1 column(``protein``) is the name of the protein.
- The 2 column(``chr``) is the name of the chromosome.
- The 3 column(``pos``) is the position of the point.

Others are optional:
- The 4 column(``strand``) is the strand position of the point.
- The 5 column(``CancerTypeNumber``) is the number of cancer where the mutation is found.
- The 6 column(``AA_pos``) is the AA position of the point.
- The 7 column(``AA_change``) is the AA_change of the point.
- The 8 column(``Consequence``) is the consequence of the point.
- The 9 column(``color``) is the specific color of the point.
- The 10 column(``type``) is the mutation type of the point.
- The 11 column(``link``) is the hyperlink address of the point.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"LOLLIPOP01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

   python NGCircos_PrepareData.py LOLLIPOP LOLLIPOP01.txt > LOLLIPOP01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally LOLLIPOP01.js is in the following:

.. code-block:: javascript

   var LOLLIPOP01 = [ "LOLLIPOP01" , {
      LOLLIPOPFillColor:"#9400D3",
      LOLLIPOPSecondColor: "#FFFFFFF",
      PointType: "circle",
      circleSize: 6,
      stroke:true,
      strokeColor: "#999999",
      strokeWidth: "1px",
      lineAutoHeight: true,
      LOLLIPOPAnimationDisplay: false,
      LOLLIPOPLineWidth: 1,
      LOLLIPOPLineColor: "#000000",
      realStart: 101219350,
   } , [
      {protein: "EGFR", chr: "7", pos: "101219410", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero"},
      {protein: "EGFR", chr: "7", pos: "101219417", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101219425", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101219431", strand: "+", CancerTypeNumber: "3", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      ......
      {protein: "EGFR", chr: "7", pos: "101220278", strand: "+", CancerTypeNumber: "3", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero"},
      {protein: "EGFR", chr: "7", pos: "101220281", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101220288", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101220295", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero"},
   ]];

``````````````````````````````````````````````````````
(2) Including LOLLIPOP data
``````````````````````````````````````````````````````

Use <script> tag to include LOLLIPOP01.js.

.. code-block:: html

   <script src="../data/data_prepare/LOLLIPOP01.js"></script>

``````````````````````````````````````````````````````````````````````````````````````
(3) Initialize LOLLIPOP data with **data tag** : **LOLLIPOP01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **LOLLIPOP01**.

.. code-block:: javascript

   NGCircos01 = new NGCircos(LOLLIPOP01,ARC01,NGCircosGenome,{ // Initialize with "LOLLIPOP01" data tag

``````````````````````````````````````````````````````````````````````````````````````
(4) Visualization of LOLLIPOP data using NG-Circos
``````````````````````````````````````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_LOLLIPOP_Module.png
   :scale: 20%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_LOLLIPOP_Module.html
   
-------------------
4.14 GENE module
-------------------
**"GENE module"** is used to display the **Gene profile**, etc. Of course, other data have similar structure can also be displayed by GENE module.

.. note:: We will use four steps to illustrate the input data preparation and how to use GENE module, below is an example.

         - Input data: `GENE01.txt <./data/data_prepare/GENE01.txt>`__
         - Input data used in NG-Circos: `GENE01.js <./data/data_prepare/GENE01.js>`__

``````````````````````````````````````````````````````
(1) GENE data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

   #chr   strand   start   end   type   name
   EGFR	+	57	965	gene	EGFR	
   EGFR	+	57	167	cds	EGFR	
   EGFR	+	185	338	cds	EGFR	
   EGFR	+	361	480	cds	EGFR	
   EGFR	+	505	636	cds	EGFR	
   EGFR	+	713	965	cds	EGFR	

Three fields are required:

- The 1 column(``chr``) is the name of the gene.
- The 2 column(``strand``) is the strand of the gene.
- The 3 column(``start``) is the start position of the gene.
- The 4 column(``end``) is the end position of the point.
- The 5 column(``type``) is the type of this fragment in gene.

Others are optional:

- The 6 column(``name``) is the neme of the fragment.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"GENE01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

   python NGCircos_PrepareData.py GENE GENE01.txt > GENE01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally GENE01.js is in the following:

.. code-block:: javascript

   var GENE01 = [ "GENE01" , {
      outerRadius: -25,
      innerRadius: -10,
      arrowGap: 2,
      arrowColor: "blue",
      arrowSize: "12px",
      cdsColor: "blue",
      cdsStrokeColor: "blue",
      cdsStrokeWidth: 1,
      utrWidth: -5,
      utrColor: "blue",
      utrStrokeColor: "blue",
      utrStrokeWidth: 1,
      } , [
        {chr: "EGFR", strand: "+", start: "57", end: "965", type: "gene", name: "EGFR"},
        {chr: "EGFR", strand: "+", start: "57", end: "167", type: "cds", name: "EGFR"},
        {chr: "EGFR", strand: "+", start: "185", end: "338", type: "cds", name: "EGFR"},
        {chr: "EGFR", strand: "+", start: "361", end: "480", type: "cds", name: "EGFR"},
        {chr: "EGFR", strand: "+", start: "505", end: "636", type: "cds", name: "EGFR""},
        {chr: "EGFR", strand: "+", start: "713", end: "965", type: "cds", name: "EGFR"},
   ]];

``````````````````````````````````````````````````````
(2) Including GENE data
``````````````````````````````````````````````````````

Use <script> tag to include GENE01.js.

.. code-block:: html

   <script src="../data/data_prepare/GENE01.js"></script>

``````````````````````````````````````````````````````````````````````````````````````
(3) Initialize GENE data with **data tag** : **GENE01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **GENE01**.

.. code-block:: javascript

   NGCircos01 = new NGCircos(GENE01,NGCircosGenome,{ // Initialize with "GENE01" data tag

``````````````````````````````````````````````````````
(4) Visualization of GENE data using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_GENE_Module.png
   :scale: 20%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_GENE_Module.html
   
-------------------
4.15 CHORD module
-------------------
**"CHORD module"** is used to display the **Relationship between gene, exon, protein...**, etc. Of course, other data have similar structure can also be displayed by CHORD module.

.. note:: We will use four steps to illustrate the input data preparation and how to use CHORD module, below is an example.

         - Input data: `CHORD01.txt <./data/data_prepare/CHORD01.txt>`__
         - Input data used in NG-Circos: `CHORD01.js <./data/data_prepare/CHORD01.js>`__

``````````````````````````````````````````````````````
(1) CHORD data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

   #	Alphaproteobacteria	Betaproteobacteria	Gammaproteobacteria	Deltaproteobacteria	Acidobacteria	Actinobacteria	Bacteroidetes	Chloroflexi	Firmicutes	Gemmatimonadetes	Planctomycetes	Thaumarchaeota	Verrucomicrobia	Ascomycota	Basidiomycota	Zygomycota
   C.CK	18.01	5.72	5.74	6.55	13.38	20.04	5.01	3.63	2.37	6.34	4.35	1.51	1.9	51.72	24.75	18.49
   C.NPK	16.12	5.75	5.85	5.67	16.88	15.95	5.24	3.74	2.34	6.97	6.15	1.21	2.37	40.28	24.18	29.3
   GC.CK	16.16	6.51	7.82	5.13	13.29	13.11	7.32	4.81	1.52	7.92	4.95	1.52	2.57	33.85	17.93	41.7
   GC.NPK	19.87	5.53	6.1	5.93	10.07	23.23	4.84	2.9	4.49	5.14	3.81	1.91	1.46	33.56	12.87	49.8

Three fields are required:

- The 1 column is the name of each row.
- The 2 column is the name of each column.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"CHORD01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

   python NGCircos_PrepareData.py CHORD CHORD01.txt > CHORD01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally CHORD01.js is in the following:

.. code-block:: javascript

   var CHORD01 = [ "CHORD01" , {
      CHORDinnerRadius: 237,
      CHORDouterRadius: 238,
      CHORDFillOpacity:0.67,
      CHORDStrokeColor: "black",
      CHORDStrokeWidth: 1,
      CHORDPadding:0.06,
      CHORDAutoFillColor: true,
      CHORDouterARC:true,
      CHORDouterARCAutoColor:true,
      CHORDouterARCText:false,
   } , [
   ['C.CK', 'C.NPK', 'GC.CK', 'GC.NPK', 'Alphaproteobacteria', 'Betaproteobacteria', 'Gammaproteobacteria', 'Deltaproteobacteria', 'Acidobacteria', 'Actinobacteria', 'Bacteroidetes', 'Chloroflexi', 'Firmicutes', 'Gemmatimonadetes', 'Planctomycetes', 'Thaumarchaeota', 'Verrucomicrobia', 'Ascomycota', 'Basidiomycota', 'Zygomycota']
   [[0, 0, 0, 0, 18.01, 5.72, 5.74, 6.55, 13.38, 20.04, 5.01, 3.63, 2.37, 6.34, 4.35, 1.51, 1.9, 51.72, 24.75, 18.49], [0, 0, 0, 0, 16.12, 5.75, 5.85, 5.67, 16.88, 15.95, 5.24, 3.74, 2.34, 6.97, 6.15, 1.21, 2.37, 40.28, 24.18, 29.3], [0, 0, 0, 0, 16.16, 6.51, 7.82, 5.13, 13.29, 13.11, 7.32, 4.81, 1.52, 7.92, 4.95, 1.52, 2.57, 33.85, 17.93, 41.7], [0, 0, 0, 0, 19.87, 5.53, 6.1, 5.93, 10.07, 23.23, 4.84, 2.9, 4.49, 5.14, 3.81, 1.91, 1.46, 33.56, 12.87, 49.8], [18.01, 16.12, 16.16, 19.87, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [5.72, 5.75, 6.51, 5.53, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [5.74, 5.85, 7.82, 6.1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [6.55, 5.67, 5.13, 5.93, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [13.38, 16.88, 13.29, 10.07, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [20.04, 15.95, 13.11, 23.23, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [5.01, 5.24, 7.32, 4.84, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [3.63, 3.74, 4.81, 2.9, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [2.37, 2.34, 1.52, 4.49, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [6.34, 6.97, 7.92, 5.14, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [4.35, 6.15, 4.95, 3.81, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1.51, 1.21, 1.52, 1.91, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1.9, 2.37, 2.57, 1.46, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [51.72, 40.28, 33.85, 33.56, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [24.75, 24.18, 17.93, 12.87, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [18.49, 29.3, 41.7, 49.8, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]
   ]];


``````````````````````````````````````````````````````
(2) Including CHORD data
``````````````````````````````````````````````````````

Use <script> tag to include CHORD01.js.

.. code-block:: html

   <script src="../data/data_prepare/CHORD01.js"></script>

``````````````````````````````````````````````````````````````````````````````````````
(3) Initialize CHORD data with **data tag** : **CHORD01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **CHORD01**.

.. code-block:: javascript

   NGCircos01 = new NGCircos(CHORD01,NGCircosGenome,{ // Initialize with "CHORD01" data tag

``````````````````````````````````````````````````````
(4) Visualization of CHORD data using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_CHORD_Module.png
   :scale: 20%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_CHORD_Module.html
   
---------------------
4.16 REDIRECT module
---------------------
**"REDIRECT module"** is used to add hyperlink for selected module. Most modules in NG-Circos are supporting this module, including **GENE HISTOGRAM CNV SCATTER SNP LOLLIPOP ARC BUBBLE**.

.. note::It is pretty easy to add REDIRECT module for your selected module, all you need to do is to add a column in your output data.

         Here we will take LOLLIPOP as an example.

``````````````````````````````````````````````````````
(1) REDIRECT data preparation in LOLLIPOP
``````````````````````````````````````````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Modify the output file you got from NGCircos_PrepareData.py
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Before, the LOLLIPOP01.js looks like this:

.. code-block:: javascript

   var LOLLIPOP01 = [ "LOLLIPOP01" , {
      LOLLIPOPFillColor:"#9400D3",
      LOLLIPOPSecondColor: "#FFFFFFF",
      PointType: "circle",
      circleSize: 6,
      stroke:true,
      strokeColor: "#999999",
      strokeWidth: "1px",
      lineAutoHeight: true,
      LOLLIPOPAnimationDisplay: false,
      LOLLIPOPLineWidth: 1,
      LOLLIPOPLineColor: "#000000",
      realStart: 101219350,
   } , [
      {protein: "EGFR", chr: "7", pos: "101219410", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero"},
      {protein: "EGFR", chr: "7", pos: "101219417", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101219425", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101219431", strand: "+", CancerTypeNumber: "3", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      ......
      {protein: "EGFR", chr: "7", pos: "101220278", strand: "+", CancerTypeNumber: "3", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero"},
      {protein: "EGFR", chr: "7", pos: "101220281", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101220288", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101220295", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero"},
   ]];

To start using REDIRECT module in LOLLIPOP, add a parameter called **link** for each mutation as the following:

.. code-block:: javascript

   var LOLLIPOP01 = [ "LOLLIPOP01" , {
      LOLLIPOPFillColor:"#9400D3",
      LOLLIPOPSecondColor: "#FFFFFFF",
      PointType: "circle",
      circleSize: 6,
      stroke:true,
      strokeColor: "#999999",
      strokeWidth: "1px",
      lineAutoHeight: true,
      LOLLIPOPAnimationDisplay: false,
      LOLLIPOPLineWidth: 1,
      LOLLIPOPLineColor: "#000000",
      realStart: 101219350,
   } , [
      {protein: "EGFR", chr: "7", pos: "101219410", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero", link: "https://www.intogen.org/search?gene=EGFR"},
      {protein: "EGFR", chr: "7", pos: "101219417", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo", link: "https://www.intogen.org/search?gene=EGFR"},
      {protein: "EGFR", chr: "7", pos: "101219425", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo", link: "https://www.intogen.org/search?gene=EGFR"},
      {protein: "EGFR", chr: "7", pos: "101219431", strand: "+", CancerTypeNumber: "3", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo", link: "https://www.intogen.org/search?gene=EGFR"},
      ......
      {protein: "EGFR", chr: "7", pos: "101220278", strand: "+", CancerTypeNumber: "3", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero", link: "https://www.intogen.org/search?gene=EGFR"},
      {protein: "EGFR", chr: "7", pos: "101220281", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo", link: "https://www.intogen.org/search?gene=EGFR"},
      {protein: "EGFR", chr: "7", pos: "101220288", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo", link: "https://www.intogen.org/search?gene=EGFR"},
      {protein: "EGFR", chr: "7", pos: "101220295", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero", link: "https://www.intogen.org/search?gene=EGFR"},
   ]];
   
See details: `REDIRECT01.js <./data/data_prepare/REDIRECT01.js>`__


``````````````````````````````````````````````````````````````````````````````````````
(2) Set **LOLLIPOPxlink** as true(default false) in NGCircos01
``````````````````````````````````````````````````````````````````````````````````````

.. note::For other modules which is supporting REDIRECT module, specific parameter is built in as well(CNVxlink, HISTOGRAMxlink, GENExlink, SNPxlink, SCATTERxlink, ARCxlink)

The code should looks like below:

.. code-block:: javascript

   NGCircos01 = new NGCircos(LOLLIPOP01,NGCircosGenome,{ 
      target:"NGCircos",
      svgWidth:900,
      svgHeight:600,
      svgClassName:"lollipop",
      ......
      LOLLIPOPxlink:true,
      ......

``````````````````````````````````````````````````````
(3) Try and see the REDIRECT in LOLLIPOP
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_REDIRECT_Module.png
   :scale: 20%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_REDIRECT_Module.html

---------------------
4.17 DOWNLOAD module
---------------------
**"DOWNLOAD module"** is used to add a download button for your SVG element. **DOWNLOAD** module provide 2 types of files for downloading(.png and .svg), users can customize the button style freely as well.

.. note::It is pretty easy to add DOWNLOAD module for your SVG element, all you need is only 2 steps.

         Here we will take LOLLIPOP as an example to show you how to download the SVG element.

``````````````````````````````````````````````````````
(1) Choose the file type for DOWNLOAD module
``````````````````````````````````````````````````````

.. note::Cause we rely on XMLHttpRequest and due to Cross-Origin Resource Sharing (CORS policy), we strongly suggest to upload your local image to a website then use the url address for hyperlink when you add a .png DOWNLOAD module and COMBINATION module both.

         For exmaple, you can upload your image to Github and then try to use the image address start with https://raw.githubusercontent.com/... as your hyperlink instead of a local address

::::::::::::::::::::::::::::::::::
For .png file
::::::::::::::::::::::::::::::::::

For .png DOWNLOAD module, we need first to create a button with the code following.

.. code-block:: html

   <div class="svg-box img-container">
      <button class="svg-action-btn download-img">Download png ↓</button>
   </div>  

If you are not familiar with the html language, don't worry, normally you don't need to change this code block, just add this to your website 

The <div> tag here is to set the button position, you can add this code block up or below the main picture.

::::::::::::::::::::::::::::::::::
For .svg file
::::::::::::::::::::::::::::::::::

For .svg DOWNLOAD module, we need first to create a button with the code following.

.. code-block:: html

   <a href="javascript:(function () { var e = document.createElement('script');if (window.location.protocol === 'https:') { e.setAttribute('src', '../lib/svg-crowbar.js'); } else { e.setAttribute('src', '../lib/svg-crowbar.js'); } e.setAttribute('class', 'svg-crowbar'); document.body.appendChild(e); })();" class="DownButtonNormal" >Download svg ↓</a>

If you are not familiar with the html language, don't worry, normally you don't need to change this code block, just add this to your website 

The <a> tag here is to set the button position, you can add this code block up or below the main picture.

``````````````````````
(2) Essential code
``````````````````````

.. note::This step is only for .png DOWNLOAD module, you can skip it if you only use .svg DOWNLOAD module.

::::::::::::::::::::::::::::::::::
For .png file
::::::::::::::::::::::::::::::::::

Add the code block below after the </script> tag of main picture and before the </body> tag:

.. code-block:: html

      <script src=../lib/saveSvgAsPng.js></script>
      <script>
                  
         (function(){
            var downloadImg = getEle(".download-img"),
               imgName = getEle("."+NGCircos1.svgClassName);
            
            //					imgScale = getEle(".img-scale");

            downloadImg.addEventListener("click",function(){
               var mySvg = getEle("."+NGCircos1.svgClassName),
                  //iImgScale = parseInt(imgScale.value) || 1,
                  oImgName = imgName.value || NGCircos1.svgClassName;
                  
            //					saveSvgAsPng(mySvg, oImgName+".png", iImgScale);
               saveSvgAsPng(mySvg, oImgName+".png");

            })

            function getEle(obj){
               var d = document;
               return d.querySelector(obj);
            }
         })()

      </script>
      
Actually, the DOWNLOAD module has already been working after this 2 steps, we still provide the third step for customizing button style.

``````````````````````````````````````````````````````
(3) Customizing the style of button
``````````````````````````````````````````````````````

You may notice both in the code block of .png and .svg DOWNLOAD module, we set a class for both button, which is **DownButtonNormal**.

You can freely customize these 2 buttons by the <style></style> tag as following:

.. code-block:: html
   
   <style>
      .DownButtonNormal{
         height: 18px;
         line-height: 18px;
         padding: 0 11px;
         background: #FFFFFF;
         border: 1px #D9D9D9 solid;
         border-radius: 3px;
         display: inline-block;
         font-size: 12px;
         outline: none;
      }
   </style>

Please add this before the <body> tag and after the </head> tag in your website.

``````````````````````````````````````````````````````
(4) Try to click the DOWNLOAD button.
``````````````````````````````````````````````````````

.. image:: _images/DataPreparationTools_DOWNLOAD_Module.png
   :scale: 20%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_DOWNLOAD_Module.html

---------------------------
4.18 AUXILIARYLINE module
---------------------------
**"AUXILIARYLINE module"** is used to display **Auxiliary line** for better explain the relationship between modules.

.. note:: We will use 3 steps to illustrate how to use AUXILIARYLINE module, below is an example.

         - Data used in NG-Circos: `AUXILIARYLINE01.js <./data/data_prepare/AUXILIARYLINE01.js>`__

``````````````````````````````````````````````````````
(1) AUXILIARYLINE data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::::::::::::::::
Data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally AUXILIARYLINE01.js is in the following:

.. code-block:: javascript

   var AUXILIARYLINE01 = [ "AUXILIARYLINE01" , {
          startX: -100,
          startY: 0,
          endX: 100,
          endY: 0,
          AUXILIARYLINEType:"curve",
          AUXILIARYLINEControlPointX:0,
          AUXILIARYLINEControlPointY:-100,
          AUXILIARYLINELineType:"dot",
          AUXILIARYLINEDashArray:4,
          AUXILIARYLINEColor: "black",
          AUXILIARYLINEWidth: 2,
          AUXILIARYLINEMarker:true,
          AUXILIARYLINEMarkerType:"arrow",
          AUXILIARYLINEMarkerColor:"black",
          AUXILIARYLINEMarkerPosition:2,
      }];

``````````````````````````````````````````````````````
(2) Including AUXILIARYLINE data
``````````````````````````````````````````````````````

Use <script> tag to include AUXILIARYLINE01.js.

.. code-block:: html

   <script src="../data/data_prepare/AUXILIARYLINE01.js"></script>

``````````````````````````````````````````````````````````````````````````````````````
(3) Initialize AUXILIARYLINE data with **data tag** : **AUXILIARYLINE01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **AUXILIARYLINE01**.

.. code-block:: javascript

   NGCircos01 = new NGCircos(AUXILIARYLINE01,NGCircosGenome,{ // Initialize with "AUXILIARYLINE01" data tag

``````````````````````````````````````````````````````````````````````````````````````
(4) Visualization of AUXILIARYLINE data using NG-Circos
``````````````````````````````````````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_AUXILIARYLINE_Module.png
   :scale: 20%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_AUXILIARYLINE_Module.html

-------------------
4.19 LEGEND module
-------------------
**"LEGEND module"** is used to display **Legend** easily for better explain each element.

.. note:: We will use 3 steps to illustrate how to use LEGEND module, below is an example.

      - Data used in NG-Circos: `LEGEND01.js <./data/data_prepare/LEGEND01.js>`__

``````````````````````````````````````````````````````
(1) LEGEND data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::::::::::::::::
Data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally LEGEND01.js is in the following:

.. code-block:: javascript

   var LEGEND1 = [ "LEGEND1" , {
      x: 300,
      y: -230,
      title: " ",
      titleSize: 16,
      titleWeight: "bold",
      GapBetweenGraphicText:5,
      GapBetweenLines:20
      } , [
         {type: "circle", color:"#1E77B4",opacity:"1.0",circleSize:"8",text: "C.CK", textSize: "14",textWeight:"normal"},
         {type: "circle", color:"#AEC7E8",opacity:"1.0",circleSize:"8",text: "C.NPK", textSize: "14",textWeight:"normal"},
         {type: "circle", color:"#FF7F0B",opacity:"1.0",circleSize:"8",text: "GC.CK", textSize: "14",textWeight:"normal"},
         {type: "circle", color:"#FFBB78",opacity:"1.0",circleSize:"8",text: "GC.NPK", textSize: "14",textWeight:"normal"},
         .....
         {type: "circle", color:"#BCBC22",opacity:"1.0",circleSize:"8",text: "Verrucomicrobia", textSize: "14",textWeight:"normal"},
         {type: "circle", color:"#DADB8D",opacity:"1.0",circleSize:"8",text: "Ascomycota", textSize: "14",textWeight:"normal"},
         {type: "circle", color:"#19BDCF",opacity:"1.0",circleSize:"8",text: "Basidiomycota", textSize: "14",textWeight:"normal"},
         {type: "circle", color:"#9ED9E5",opacity:"1.0",circleSize:"8",text: "Zygomycota", textSize: "14",textWeight:"normal"},
      ]];

``````````````````````````````````````````````````````
(2) Including LEGEND data
``````````````````````````````````````````````````````

Use <script> tag to include LEGEND01.js.

.. code-block:: html

   <script src="../data/data_prepare/LEGEND01.js"></script>

``````````````````````````````````````````````````````````````````````````````````````
(3) Initialize LEGEND data with **data tag** : **LEGEND01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **LEGEND01**.

.. code-block:: javascript

   NGCircos01 = new NGCircos(LEGEND01,NGCircosGenome,{ // Initialize with "LEGEND01" data tag

``````````````````````````````````````````````````````
(4) Visualization of LEGEND data using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_LEGEND_Module.png
   :scale: 20%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_LEGEND_Module.html
   
--------------------
4.20 COMPARE module
--------------------
**"COMPARE module"** can display two groups of chromosome in half circle as well as the modules in each chromosome.

.. note::It is pretty easy to add COMPARE module for all your modules and chromosome, we will use 3 steps to illustrate how to use COMPARE module.

``````````````````````````````````````````````````````
(1) Add 2 groups of chromosome
``````````````````````````````````````````````````````

::::::::::::::::::::::::::::::::::
Modify the genome configuration
::::::::::::::::::::::::::::::::::

Before add the COMPARE module, the genome configuration looks like this:

.. code-block:: javascript

   var NGCircosGenome = [
   [
      ["chr8",1000],
   ]
   ];
   
To start using COMPARE module, we will add another group of chromosome as the following:

.. code-block:: javascript

   var NGCircosGenome = [
   [
      ["chr8",1000],
   ],[
      ["chr8",1000],
   ]
   ];

``````````````````````````````````````````````````````````````````````````````````````
(2) Set **compareEvent** as true(default false) in NGCircos01
``````````````````````````````````````````````````````````````````````````````````````

The code should looks like below:

.. code-block:: javascript

   NGCircos01 = new NGCircos(LOLLIPOP01,NGCircosGenome,{ 
      target:"NGCircos",
      svgWidth:900,
      svgHeight:600,
      svgClassName:"lollipop",
      ......
      compareEvent:true,
      compareEventGroupGapRate:0.2,      //Empty gap rate
      compareEventGroupDistance:100,      //Distance between 2 groups
      ......

``````````````````````````````````````````````````````````````````````````````````````
(3) Assign group number in each module with **compareGroup** 
``````````````````````````````````````````````````````````````````````````````````````

Before add the COMPARE module, the COMPARE01.js looks like this:

.. code-block:: javascript

   var WIG01 = [ "WIG01" , {
      maxRadius: 200,
      minRadius: 150,
      WIGStrokeColor: "#3D6390",
      WIGColor: "#3D6390",
      WIGStrokeType:"cardinal" //linear,cardinal,basis,monotone
   } , [
      {chr:"chr8",pos:"0.09827044025157233",value:"0.0199"},
      {chr:"chr8",pos:"1.3266509433962264",value:"0.0199"},
      {chr:"chr8",pos:"2.5550314465408803",value:"0.0199"},
      {chr:"chr8",pos:"3.7834119496855347",value:"0.0498"},
      ......
      {chr:"chr8",pos:"996.314858490566",value:"0.0299"},
      {chr:"chr8",pos:"997.5432389937107",value:"0.0398"},
      {chr:"chr8",pos:"998.7716194968554",value:"0.0896"},
      {chr:"chr8",pos:"1000.0",value:"0.1195"},
   ]];

   var WIG02 = [ "WIG02" , {
      maxRadius: 200,
      minRadius: 150,
      WIGStrokeColor: "#3D6390",
      WIGColor: "#3D6390",
      WIGStrokeType:"cardinal" //linear,cardinal,basis,monotone
   } , [
      {chr:"chr8",pos:"0.024557353699565337",value:"5"},
      {chr:"chr8",pos:"0.5157044276908721",value:"5"},
      {chr:"chr8",pos:"1.0068515016821786",value:"4"},
      {chr:"chr8",pos:"1.4979985756734855",value:"4"},
      ......
      {chr:"chr8",pos:"998.5265587780261",value:"1"},
      {chr:"chr8",pos:"999.0177058520175",value:"1"},
      {chr:"chr8",pos:"999.5088529260087",value:"1"},
      {chr:"chr8",pos:"1000.0",value:"1"},
   ]];
   
To start using COMPARE module, we will add **compareGroup** (default 1) of chromosome as the following:

.. code-block:: javascript

   var WIG01 = [ "WIG01" , {
      compareGroup:2,
      maxRadius: 200,
      minRadius: 150,
      WIGStrokeColor: "#3D6390",
      WIGColor: "#3D6390",
      WIGStrokeType:"cardinal" //linear,cardinal,basis,monotone
   } , [
      {chr:"chr8",pos:"0.09827044025157233",value:"0.0199"},
      {chr:"chr8",pos:"1.3266509433962264",value:"0.0199"},
      {chr:"chr8",pos:"2.5550314465408803",value:"0.0199"},
      {chr:"chr8",pos:"3.7834119496855347",value:"0.0498"},
      ......
      {chr:"chr8",pos:"996.314858490566",value:"0.0299"},
      {chr:"chr8",pos:"997.5432389937107",value:"0.0398"},
      {chr:"chr8",pos:"998.7716194968554",value:"0.0896"},
      {chr:"chr8",pos:"1000.0",value:"0.1195"},
   ]];

   var WIG02 = [ "WIG02" , {
      compareGroup:1,
      maxRadius: 200,
      minRadius: 150,
      WIGStrokeColor: "#3D6390",
      WIGColor: "#3D6390",
      WIGStrokeType:"cardinal" //linear,cardinal,basis,monotone
   } , [
      {chr:"chr8",pos:"0.024557353699565337",value:"5"},
      {chr:"chr8",pos:"0.5157044276908721",value:"5"},
      {chr:"chr8",pos:"1.0068515016821786",value:"4"},
      {chr:"chr8",pos:"1.4979985756734855",value:"4"},
      ......
      {chr:"chr8",pos:"998.5265587780261",value:"1"},
      {chr:"chr8",pos:"999.0177058520175",value:"1"},
      {chr:"chr8",pos:"999.5088529260087",value:"1"},
      {chr:"chr8",pos:"1000.0",value:"1"},
   ]];
   
See details: `COMPARE01.js <./data/data_prepare/COMPARE01.js>`__

``````````````````````````````````````````````````````
(4) Try and see the COMPARE
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_COMPARE_Module.png
   :scale: 20%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_COMPARE_Module.html

-------------------------
4.21 COMBINATION module
-------------------------
**"COMBINATION module"** can display image and graph with mouse event, currently we only supply SNP module for COMBINATION module, more modules will be adapted and updated in the future.

.. note:: We will use four steps to illustrate the input data preparation and how to use COMBINATION module, below is an example.

        - Input data: `COMBINATION_SNP01.txt <./data/data_prepare/COMBINATION_SNP01.txt>`__
        - Input data used in NG-Circos: `COMBINATION_SNP01.js <./data/data_prepare/COMBINATION_SNP01.js>`__

``````````````````````
(1) Data preparation
``````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

Notice that this data has more column than in SNP01.txt, which contains the information needed in COMBINATION. For graph, we provide columns(For example, here called eas, sas, afr, eur, amr, which is the five poplation from 1000 genome project) to store the necessary information needed for 3 kinds of graph. For image, there is a column called image to store the url address.

.. code-block:: html

   #chr	pos	value	des   color	eas	sas	afr	eur	amr	image
   10	100315722	20.2218	rs603424
   10	101219450	19	rs11190870
   10	103086421	25.1549	rs11191548
   10	121577821	169.699	rs2981579	#991ECC	0.551	0.61	0.339	0.549	0.57	https://raw.githubusercontent.com/mrcuizhe/Image_NGCircos/master/combination_snp/EUR.rs2981579.400kb-1.png
    ......
   X	5266661	24.699	rs6638512
   X	67343176	90.699	rs2497938
   8	19986711	149	rs12678919	#991ECC	0.12	0.08	0.116	0.13	0.06	https://raw.githubusercontent.com/mrcuizhe/Image_NGCircos/master/combination_snp/EUR.rs12678919.400kb-1.png
   X	79241621	32.699	rs5912838

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``pos``) is the position of the SNP.
- The 3 column(``value``) is the value(density, P-value, etc.) of the SNP.
- The 4 column(``des``) is the description of the SNP.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"COMBINATION_SNP01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

   python NGCircos_PrepareData.py COMBINATION_SNP COMBINATION_SNP01.txt > COMBINATION_SNP01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, such as ``minRadius``, and finally COMBINATION_SNP01.js is in the following:

.. code-block:: javascript

   var SNP01 = [ "SNP01" , {
     maxRadius: 205,
     minRadius: 153,
     SNPFillColor: "#9400D3",
     PointType: "circle",
     circleSize: 2,
     rectWidth: 2,
     rectHeight: 2
   } , [
     {chr: "10", pos: "100315722", value: "20.2218", des: "rs603424", color: "rgb(153,102,0)"},
     {chr: "10", pos: "101219450", value: "19", des: "rs11190870", color: "rgb(153,102,0)"},
     {chr: "10", pos: "103086421", value: "25.1549", des: "rs11191548", color: "rgb(153,102,0)"},
     {chr: "10", pos: "112998590", value: "74.0969", des: "rs7903146", color: "rgb(153,102,0)"},
     {chr: "10", pos: "121577821", value: "169.699", des: "rs2981579", color: "rgb(153,102,0)", index: "1", image: "https://raw.githubusercontent.com/mrcuizhe/Image_NGCircos/master/combination_snp/EUR.rs2981579.400kb-1.png"},
      ......
     {chr: "8", pos: "19986711", value: "149", des: "rs12678919", color: "rgb(102,102,102)", index: "66", image: "https://raw.githubusercontent.com/mrcuizhe/Image_NGCircos/master/combination_snp/EUR.rs12678919.400kb-1.png"},
     {chr: "X", pos: "67343176", value: "90.699", des: "rs2497938", color: "rgb(153,153,153)"},
     {chr: "X", pos: "69578860", value: "18.1549", des: "rs11796357", color: "rgb(153,153,153)"},
     {chr: "X", pos: "79241621", value: "32.699", des: "rs5912838", color: "rgb(153,153,153)"},
   ],[
      ["eas","sas","afr","eur"],
      ["0.551","0.61","0.339","0.549"],
      ["0.583","0.54","0.875","0.348"],
      ["0.953","0.74","0.601","0.786"],
      ["0.759","0.81","0.94","0.907"],
      ["0.296","0.12","0.09","0.365"],
      ["0.97","0.82","0.963","0.847"],
      ["0.941","0.85","0.181","0.726"],
      ["0.565","0.33","0.183","0.311"],
      ["0.567","0.16","0.697","0.363"],
      ["0.951","0.71","0.638","0.638"],
      ["0.204","0.29","0.411","0.346"],
      ["0.216","0.0","0.001","0.0"],
      ["0.063","0.24","0.239","0.263"],
      ["0.123","0.04","0.014","0.161"],
      ["0.189","0.35","0.424","0.409"],
      ["0.002","0.07","0.028","0.636"],
      ["0.0","0.0","0.004","0.014"],
      ["0.168","0.29","0.411","0.414"],
      ["0.0","0.01","0.003","0.062"],
      ["0.34","0.44","0.213","0.441"],
      ["0.001","0.06","0.135","0.241"],
      ["0.025","0.2","0.16","0.304"],
      ["0.001","0.07","0.04","0.242"],
      ["0.001","0.02","0.006","0.121"],
      ["0.012","0.08","0.147","0.110"],
      ["0.98","0.89","0.733","0.85"],
      ["0.614","0.36","0.66","0.31"],
      ["0.877","0.63","0.62","0.767"],
      ["0.211","0.28","0.077","0.328"],
      ["0.115","0.13","0.078","0.298"],
      ["0.154","0.28","0.173","0.291"],
      ["0.28","0.44","0.281","0.5"],
      ["0.375","0.22","0.205","0.367"],
      ["0.13","0.44","0.493","0.298"],
      ["0.13","0.44","0.486","0.298"],
      ["0.009","0.16","0.867","0.23"],
      ["0.005","0.15","0.628","0.216"],
      ["0.005","0.14","0.617","0.21"],
      ["0.006","0.14","0.618","0.208"],
      ["0.572","0.46","0.628","0.327"],
      ["0.297","0.36","0.52","0.417"],
      ["0.441","0.24","0.3","0.232"],
      ["0.3","0.54","0.094","0.583"],
      ["0.013","0.2","0.48","0.214"],
      ["0.041","0.05","0.161","0.031"],
      ["0.959","0.87","0.816","0.89"],
      ["0.864","0.87","0.815","0.89"],
      ["0.052","0.2","0.084","0.143"],
      ["0.315","0.31","0.36","0.273"],
      ["0.001","0.01","0.002","0.047"],
      ["0.001","0.01","0.002","0.047"],
      ["0.052","0.07","0.042","0.187"],
      ["0.52","0.46","0.344","0.382"],
      ["0.994","0.98","0.973","0.88"],
      ["0.354","0.38","0.236","0.451"],
      ["0.365","0.31","0.28","0.393"],
      ["0.003","0.23","0.268","0.305"],
      ["0.002","0.09","0.164","0.242"],
      ["0.676","0.34","0.475","0.422"],
      ["0.794","0.39","0.326","0.403"],
      ["0.365","0.31","0.28","0.393"],
      ["0.455","0.41","0.08","0.54"],
      ["0.005","0.02","0.449","0.082"],
      ["0.006","0.06","0.277","0.104"],
      ["0.299","0.34","0.851","0.057"],
      ["0.999","0.97","0.688","0.912"],
      ["0.12","0.08","0.116","0.13"]
      ]
   ];

``````````````````````
(2) Including data
``````````````````````

Use <script> tag to include SNP02.js.

.. code-block:: html

   <script src="../data/data_prepare/SNP02.js"></script>

``````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
(3) Initialize data with **data tag** : **SNP02** and set **SNPMouseEvent** and **SNPMouseCombinationEvent** to true
``````````````````````````````````````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **SNP02** and the parameters is below.

.. code-block:: javascript

   NGCircos01 = new NGCircos(SNP02,NGCircosGenome,{  // Initialize with "SNP02" data tag
         target:"NGCircos",
         svgWidth:900,
         svgHeight:600,
         svgClassName:"lollipop",
         ......
         SNPMouseEvent:true,
         SNPMouseCombinationEvent:true,
         SNPMouseCombinationImageDisplay:true,
         SNPMouseCombinationImageTitle:"LD",
         SNPMouseCombinationImageTitleSize:20,
         SNPMouseCombinationImageTitleWeight:"bold",
         SNPMouseCombinationImageTitleColor:"black",
         SNPMouseCombinationImagePositionX:300,
         SNPMouseCombinationImagePositionY:-242,
         SNPMouseCombinationImageHeight:200,
         SNPMouseCombinationImageWidth:400,
         SNPMouseCombinationGraphDisplay:true,
         SNPMouseCombinationGraphTitle:"Mutation in population",
         SNPMouseCombinationGraphTitleSize:20,
         SNPMouseCombinationGraphTitleWeight:"bold",
         SNPMouseCombinationGraphTitleColor:"black",
         SNPMouseCombinationGraphType:"histogram",   //histogram,pie,line
         SNPMouseCombinationGraphPositionX:350,
         SNPMouseCombinationGraphPositionY:200,
         SNPMouseCombinationGraphHeight:200,
         SNPMouseCombinationGraphWidth:300,
         SNPMouseCombinationGraphHistogramBarColor:"#99CCFE",
         SNPMouseCombinationGraphHistogramPadding:30,
         SNPMouseCombinationGraphHistogramPositionCorrectX:10,
         SNPMouseCombinationGraphPieAutoColor:true,
         SNPMouseCombinationGraphPieColor:["black","blue","orange","red","green"],
         SNPMouseCombinationGraphPieSize:100,
         SNPMouseCombinationGraphPieStroke:true,
         SNPMouseCombinationGraphPieStrokeColor:"black",
         SNPMouseCombinationGraphPieStrokeWidth:1,
         SNPMouseCombinationGraphPieOpacity:1.0,
         SNPMouseCombinationGraphLineType:"linear",
         SNPMouseCombinationGraphLineColor:"black",
         SNPMouseCombinationGraphLineWidth:1,
         SNPMouseCombinationGraphLinePoint:true,
         SNPMouseCombinationGraphLinePointSize:5,
         SNPMouseCombinationGraphLinePointAutoColor:true,
         SNPMouseCombinationGraphLinePointColor:["black","blue","orange","red","green"],
         SNPMouseCombinationGraphLinePointStroke:true,
         SNPMouseCombinationGraphLinePointStrokeColor:"black",
         SNPMouseCombinationGraphLinePointStrokeWidth:1,
         SNPMouseCombinationGraphLinePointOpacity:1,
         SNPMouseCombinationGraphLinePositionCorrectX:45,
         SNPMouseCombinationTextDisplay:true,
         SNPMouseCombinationTextColor:"#666666",
         SNPMouseCombinationTextSize:13,
         SNPMouseCombinationTextWeight:"bold",
         SNPMouseCombinationTextPositionCorrectX:45,
         SNPMouseCombinationTextPositionCorrectY:40,
         ......
   }

``````````````````````````````````````````````````````````````````````````````````````
(4) Visualization of COMBINATION with SNP module using NG-Circos
``````````````````````````````````````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_COMBINATION_SNP_Module.png
   :scale: 20%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_COMBINATION_SNP_Module.html

-------------------
4.22 BUBBLE module
-------------------
**"BUBBLE module"** is used to display the **Gene expression data** as well as its classification, etc. Of course, other data have similar structure can also be displayed by BUBBLE module.

.. note:: We will use four steps to illustrate the input data preparation and how to use BUBBLE module, below is an example.

         - Input data: `BUBBLE01.txt <./data/data_prepare/BUBBLE01.txt>`__
         - Input data used in NG-Circos: `BUBBLE01.js <./data/data_prepare/BUBBLE01.js>`__

``````````````````````````````````````````````````````
(1) BUBBLE data preparation
``````````````````````````````````````````````````````

::::::::::::::::::::
Input data
::::::::::::::::::::

Users should prepare the input data in the following format (separated by tabs).

.. code-block:: html

   #chr	start	end	name	value   color   layer
   chr6	1	100	TP53	0.1	red	3
   chr6	100	200	TP53	0.4	blue	3
   chr6	200	300	TP53	0.8	green	3
   chr6	300	400	TP53	0.9	red	3
   ......
   chr6	600	700	TP53	0.8	red	1
   chr6	700	800	TP53	0.2	blue	1
   chr6	800	900	TP53	0.6	green	1
   chr6	900	1000	TP53	0.5	green	1

Five fields are required:

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``start``) is the start of the region.
- The 3 column(``end``) is the end of the region.
- The 4 column(``name``) is the name of the bubble.
- The 5 column(``value``) is the value of the bubble.
- The 6 column(``color``) is the specific color of the bubble.
- The 7 column(``layer``) is the layer of the bubble.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Save the input data to **"BUBBLE01.txt"**, Use **"NGCircos_PrepareData.py"** to prepare data
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. code-block:: shell

   python NGCircos_PrepareData.py BUBBLE BUBBLE01.txt > BUBBLE01.js

::::::::::::::::::::::::::::::::::
Output data used in NG-Circos
::::::::::::::::::::::::::::::::::

Change the default configuration, and finally BUBBLE01.js is in the following:

.. code-block:: javascript

   var BUBBLE01 = [ "BUBBLE01" , {
      minRadius: 20,
      maxRadius: 80,
      blockStroke:true,
      blockStrokeColor:"grey",
      blockFill:false,
      blockFillColor:"white",
      bubbleMaxSize:10,
      bubbleMinSize:2,
      maxColor: "red",
      minColor: "yellow",
      totalLayer:3,
   } , [
      {chr: "chr6", start: "1", end: "100", name: "TP53", value: "0.1", color: "red", layer: "3"},
      {chr: "chr6", start: "100", end: "200", name: "TP53", value: "0.4", color: "blue", layer: "3"},
      {chr: "chr6", start: "200", end: "300", name: "TP53", value: "0.8", color: "green", layer: "3"},
      {chr: "chr6", start: "300", end: "400", name: "TP53", value: "0.9", color: "red", layer: "3"},
      ......
      {chr: "chr6", start: "600", end: "700", name: "TP53", value: "0.8", color: "red", layer: "1"},
      {chr: "chr6", start: "700", end: "800", name: "TP53", value: "0.2", color: "blue", layer: "1"},
      {chr: "chr6", start: "800", end: "900", name: "TP53", value: "0.6", color: "green", layer: "1"},
      {chr: "chr6", start: "900", end: "1000", name: "TP53", value: "0.5", color: "green", layer: "1"},
   ]];

``````````````````````````````````````````````````````
(2) Including BUBBLE data
``````````````````````````````````````````````````````

Use <script> tag to include BUBBLE01.js.

.. code-block:: html

   <script src="../data/data_prepare/BUBBLE01.js"></script>

``````````````````````````````````````````````````````````````````````````````````````
(3) Initialize BUBBLE data with **data tag** : **BUBBLE01**
``````````````````````````````````````````````````````````````````````````````````````

Here the data's **data tag** is defined as **BUBBLE01**.

.. code-block:: javascript

   NGCircos01 = new NGCircos(BUBBLE01,NGCircosGenome,{ // Initialize with "BUBBLE01" data tag

``````````````````````````````````````````````````````
(4) Visualization of BUBBLE data using NG-Circos
``````````````````````````````````````````````````````
.. image:: _images/DataPreparationTools_BUBBLE_Module.png
   :scale: 20%
   :alt: alternate text
   :align: left
   :target: pages/DataPreparationTools_BUBBLE_Module.html


===========================
5. API: Main configuration
===========================

**"Main configuration"** is the main configuration part of NG-Circos and mainly divided into four classes: **"Customize SVG"**, **"Customize genome"**, **"Customize Events"** and **"Customize Tooltips"**.

.. list-table::
   :widths: 30 90
   :header-rows: 1

   * - Class of Main configuration
     - Major function
   * - **Customize SVG**
     - Customize the length, width and position of the canvas(SVG)...
   * - **Customize genome**
     - Customize the wtidth and color of the genome; Customize the attributes of the ticks; Customize the attributes of the genome labels...
   * - **Customize Events**
     - Customize text drag event, zoom translation event and mouse binding event...
   * - **Customize Tooltips**
     - Customize content and style of tooltips...

-------------------
5.1 Customize SVG
-------------------
**Customize SVG** class is used to customize the length, width and position of the canvas(SVG).

````````````````````````````````
(1)All configuration parameters
````````````````````````````````
Here we show all the configuration parameters in **Customize SVG** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize SVG
	     target : "NGCircos",
	     svgWidth : 900,
	     svgHeight : 600,
        svgClassName: "NGCircos",
	  });

```````````````````````````````
(2)Configuration and examples
```````````````````````````````

- ``target``
    default "NGCircos", SVG position in html, where <div> id is "NGCircos"

- ``svgWidth``
    default 900, SVG width

- ``svgHeight``
    default 600, SVG height
   
- ``svgClassName``
   default NGCircos, SVG class name

**Example**: change the size of SVG

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

	  svgWidth : 900,
	  svgHeight : 600,

     - .. code-block:: javascript

	  svgWidth : 600,
	  svgHeight : 400,

   * - Image change

     - .. image:: _images/API_main_customize_svg01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_svg01_before.html
     
     - .. image:: _images/API_main_customize_svg01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_svg01_after.html

---------------------
5.2 Customize genome
---------------------
**Customize genome** class is used to customize the width and color of the genome, the attributes of the ticks and the attributes of the genome labels.

`````````````````````````````````
(1)All configuration parameters
`````````````````````````````````
Here we show all the configuration parameters in **Customize genome** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize genome
	     chrPad : 0.04,
	     innerRadius : 246,
	     outerRadius : 270,
	     genomeFillColor : ["rgb(153,102,0)", "rgb(102,102,0)", "rgb(153,153,30)", "rgb(204,0,0)","rgb(255,0,0)", "rgb(255,0,204)", "rgb(255,204,204)", "rgb(255,153,0)", "rgb(255,204,0)", "rgb(255,255,0)", "rgb(204,255,0)", "rgb(0,255,0)","rgb(53,128,0)", "rgb(0,0,204)", "rgb(102,153,255)", "rgb(153,204,255)", "rgb(0,255,255)", "rgb(204,255,255)", "rgb(153,0,204)", "rgb(204,51,255)","rgb(204,153,255)", "rgb(102,102,102)", "rgb(153,153,153)", "rgb(204,204,204)"],
	     genomeBorder : {
                "display" : true,
                "borderColor" : "#000",
                "borderSize" : 0.5
             },
	     ticks : {
                "display" : true,
                "len" : 5,
                "color" : "#000",
                "textSize" : 10,
                "textColor" : "#000",
                "scale" : 30000000
             },
	     genomeLabel : {
                "display" : true,
                "textSize" : 15,
                "textColor" : "#000",
                "dx" : 0.028,
                "dy" : "-0.55em"
             },
	  });

```````````````````````````````
(2)Configuration and examples
```````````````````````````````

- ``chrPad``
    default 0.04, distance between chromosomes

- ``innerRadius``
    default 246, inner radius of chromosome

- ``outerRadius``
    default 270, outer radius of chromosome

- ``genomeFillColor``
    default ["rgb(153,102,0)", "rgb(102,102,0)", "rgb(153,153,30)", "rgb(204,0,0)","rgb(255,0,0)", "rgb(255,0,204)", "rgb(255,204,204)", "rgb(255,153,0)", "rgb(255,204,0)", "rgb(255,255,0)", "rgb(204,255,0)", "rgb(0,255,0)","rgb(53,128,0)", "rgb(0,0,204)", "rgb(102,153,255)", "rgb(153,204,255)", "rgb(0,255,255)", "rgb(204,255,255)", "rgb(153,0,204)", "rgb(204,51,255)","rgb(204,153,255)", "rgb(102,102,102)", "rgb(153,153,153)", "rgb(204,204,204)"] , an array of UCSC chromosome color

**Example**: change the width of genome; change distance between chromosomes; change color of chromosomes.

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

	  chrPad:0.01,
	  innerRadius:246,
	  outerRadius:270,
	  genomeFillColor:["green", "grey"],

     - .. code-block:: javascript

	  chrPad:0.05,
	  innerRadius:266,
	  outerRadius:270,
	  genomeFillColor:["red", "black"],

   * - Image change

     - .. image:: _images/API_main_customize_genome01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_genome01_before.html
     
     - .. image:: _images/API_main_customize_genome01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_genome01_after.html

:::::::::::::
genomeBorder
:::::::::::::
.. code-block:: javascript

             genomeBorder : {
                "display" : true,
                "borderColor" : "#000",
                "borderSize" : 0.5
             },

- ``display``
    default true, [true/false], dispaly/not dispaly genome border

- ``borderColor``
    default "#000", genome border color

- ``borderSize``
    default 0.5, genome border size

**Example**: change the width and color of genome border

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          genomeBorder : {
             "display" : true,
             "borderColor" : "#000",
             "borderSize" : 0.5
          },

     - .. code-block:: javascript

          genomeBorder : {
             "display" : true,
             "borderColor" : "yellow",
             "borderSize" : 2
          },

   * - Image change

     - .. image:: _images/API_main_customize_genome02_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_genome02_before.html
     
     - .. image:: _images/API_main_customize_genome02_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_genome02_after.html

:::::::::::::
ticks
:::::::::::::
.. code-block:: javascript

             ticks : {
                "display" : true,
                "len" : 5,
                "color" : "#000",
                "textSize" : 10,
                "textColor" : "#000",
                "scale" : 30000000,
                "realLength":false,
                "offset": 0 ,
             },

- ``display``
    default true, [true/false], dispaly/not dispaly genome ticks

- ``len``
    default 5, length of genome ticks

- ``color``
    default "#000", color of genome ticks

- ``textSize``
    default 10, size of genome ticks text

- ``textColor``
    default "#000", color of genome ticks text

- ``scale``
    default 30000000, unit scale of genome ticks
   
- ``realLength``
    default false, whether ticks display the real length of genome or not
   
- ``offset``
    default 0, the offset from the real length of genome, which can help users display the realistic ticks of genome.

**Example**: change the length and color of ticks; change the size and color of tick texts

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          ticks : {
             "display" : true,
             "len" : 5,
             "color" : "#000",
             "textSize" : 10,
             "textColor" : "#000",
             "scale" : 30000000,
             "realLength" : false,
             "offset": 0 ,
          },

     - .. code-block:: javascript

          ticks : {
             "display" : true,
             "len" : 7,
             "color" : "red",
             "textSize" : 15,
             "textColor" : "red",
             "scale" : 50000000,
             "realLength" : false,
             "offset": 0 ,
          },

   * - Image change

     - .. image:: _images/API_main_customize_genome03_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_genome03_before.html
     
     - .. image:: _images/API_main_customize_genome03_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_genome03_after.html

:::::::::::::
genomeLabel
:::::::::::::
.. code-block:: javascript

             genomeLabel : {
                "display" : true,
                "textSize" : 15,
                "textColor" : "#000",
                "dx" : 0.028,
                "dy" : "-0.55em"
             }

- ``display``
    default true, [true/false], dispaly/not dispaly genome label

- ``textSize``
    default 15, size of genome label text

- ``textColor``
    default "#000", color of genome label text

- ``dx``
    default 0.028, rotation value of genome label text

- ``dy``
    default "-0.55em", distance between center and genome label text

**Example**: change the color and size of genome label

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          genomeLabel : {
            "display" : true,
            "textSize" : 15,
            "textColor" : "#000",
            "dx" : 0.028,
            "dy" : "-0.55em"
         },

     - .. code-block:: javascript

          genomeLabel : {
            "display" : true,
            "textSize" : 17,
            "textColor" : "red",
            "dx" : 0.028,
            "dy" : "-0.55em"
         },

   * - Image change

     - .. image:: _images/API_main_customize_genome04_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_genome04_before.html
     
     - .. image:: _images/API_main_customize_genome04_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_genome04_after.html

---------------------
5.3 Customize Events
---------------------
**Customize Events** class is used to customize text drag event, zoom translation event and mouse binding event.

```````````````````
 zoom event
```````````````````

Here we show how to customize the zoom event.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     zoom : false,
	  });

- ``zoom``
    default false, [true/false], enable/disable SVG zoom and translation

**Example**: open the zoom event to make SVG enable to zoom and translation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

	  zoom : false,

     - .. code-block:: javascript

	  zoom : true,

   * - Image change

     - .. image:: _images/API_main_customize_events_zoom01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_zoom01_before.html
     
     - .. image:: _images/API_main_customize_events_zoom01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_zoom01_after.html

```````````````````
 TEXT module
```````````````````

Here we show how to customize the TEXTModuleDragEvent event.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     TEXTModuleDragEvent : true,
	  });

- ``TEXTModuleDragEvent``
    default true, [true/false], open/not open TEXT module label drag event

**Example**: open TEXT module label drag event

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

	  TEXTModuleDragEvent : false,

     - .. code-block:: javascript

	  TEXTModuleDragEvent : true,

   * - Image change

     - .. image:: _images/API_main_customize_events_TEXT01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_TEXT01_before.html
     
     - .. image:: _images/API_main_customize_events_TEXT01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_TEXT01_after.html

```````````````````
 SNP module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in SNP module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events -SNP module
             SNPMouseEvent : true,
             SNPMouseClickDisplay : false,
             SNPMouseClickColor : "red",
             SNPMouseClickCircleSize : 4,
             SNPMouseClickCircleOpacity : 1.0,
             SNPMouseClickCircleStrokeColor : "#F26223",
             SNPMouseClickCircleStrokeWidth : 0,
             SNPMouseClickTextFromData : "fourth",
             SNPMouseClickTextOpacity : 1.0,
             SNPMouseClickTextColor : "red",
             SNPMouseClickTextSize : 8,
             SNPMouseClickTextPostionX : 1.0,
             SNPMouseClickTextPostionY : 10.0,
             SNPMouseClickTextDrag : true,
             SNPMouseDownDisplay : false,
             SNPMouseDownColor : "green",
             SNPMouseDownCircleSize : 4,
             SNPMouseDownCircleOpacity : 1.0,
             SNPMouseDownCircleStrokeColor : "#F26223",
             SNPMouseDownCircleStrokeWidth : 0,
             SNPMouseEnterDisplay : false,
             SNPMouseEnterColor : "yellow",
             SNPMouseEnterCircleSize : 4,
             SNPMouseEnterCircleOpacity : 1.0,
             SNPMouseEnterCircleStrokeColor : "#F26223",
             SNPMouseEnterCircleStrokeWidth : 0,
             SNPMouseLeaveDisplay : false,
             SNPMouseLeaveColor : "pink",
             SNPMouseLeaveCircleSize : 4,
             SNPMouseLeaveCircleOpacity : 1.0,
             SNPMouseLeaveCircleStrokeColor : "#F26223",
             SNPMouseLeaveCircleStrokeWidth : 0,
             SNPMouseMoveDisplay : false,
             SNPMouseMoveColor : "red",
             SNPMouseMoveCircleSize : 2,
             SNPMouseMoveCircleOpacity : 1.0,
             SNPMouseMoveCircleStrokeColor : "#F26223",
             SNPMouseMoveCircleStrokeWidth : 0,
             SNPMouseOutDisplay : false,
             SNPMouseOutAnimationTime : 500,
             SNPMouseOutColor : "red",
             SNPMouseOutCircleSize : 2,
             SNPMouseOutCircleOpacity : 1.0,
             SNPMouseOutCircleStrokeColor : "red",
             SNPMouseOutCircleStrokeWidth : 0,
             SNPMouseUpDisplay : false,
             SNPMouseUpColor : "grey",
             SNPMouseUpCircleSize : 4,
             SNPMouseUpCircleOpacity : 1.0,
             SNPMouseUpCircleStrokeColor : "#F26223",
             SNPMouseUpCircleStrokeWidth : 0,
             SNPMouseOverDisplay : false,
             SNPMouseOverColor : "red",
             SNPMouseOverCircleSize : 2,
             SNPMouseOverCircleOpacity : 1.0,
             SNPMouseOverCircleStrokeColor : "#F26223",
             SNPMouseOverCircleStrokeWidth : 3,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``SNPMouseEvent``
    default true, [true/false], open/not open mouse event of SNP module

::::::::::::::::::::
 Mouse click
::::::::::::::::::::

- ``SNPMouseClickDisplay``
    default true, [true/false], open/not open mouse click event of SNP module

- ``SNPMouseClickColor``
    default "red", "none" means no change, element change color after click the element

- ``SNPMouseClickCircleSize``
    default 4, "none" means no change, element change circle size after click the element.

- ``SNPMouseClickCircleOpacity``
    default 1.0, "none" means no change, element change opacity after click the element

- ``SNPMouseClickCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after click the element.

- ``SNPMouseClickCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after click the element.

- ``SNPMouseClickTextFromData``
    default "fourth", first,second,third,fourth column data click to show 

- ``SNPMouseClickTextOpacity``
    default 1.0, text opacity after click the element

- ``SNPMouseClickTextColor``
    default "red", text color after click the element

- ``SNPMouseClickTextSize``
    default 8, text size after click the element

- ``SNPMouseClickTextPostionX``
    default 1.0, text x position after click the element

- ``SNPMouseClickTextPostionY``
    default 10.0, text y position after click the element

- ``SNPMouseClickTextDrag``
    default true, [true/false], open/not open text drag function

**Example**: change the circle size and color when mouse click; change the annotated text content when mouse click;

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          SNPMouseClickColor : "red",
          SNPMouseClickCircleSize : 4,
          SNPMouseClickTextFromData : "second",

     - .. code-block:: javascript

          SNPMouseClickColor : "blue",
          SNPMouseClickCircleSize : 8,
          SNPMouseClickTextFromData : "fourth",

   * - Image change

     - .. image:: _images/API_main_customize_events_SNP01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP01_before.html
     
     - .. image:: _images/API_main_customize_events_SNP01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP01_after.html

::::::::::::::::::::
 Mouse down
::::::::::::::::::::

- ``SNPMouseDownDisplay``
    default false, [true/false], open/not open mouse mouse down event of SNP module

- ``SNPMouseDownColor``
    default "green", "none" means no change, element change color after mouse down the element

- ``SNPMouseDownCircleSize``
    default 4, "none" means no change, element change circle size after mouse down the element.

- ``SNPMouseDownCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse down the element

- ``SNPMouseDownCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse down the element.

- ``SNPMouseDownCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse down the element.

**Example**: change the color, size, opacity and stroke color of the circle when mouse down.

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          SNPMouseDownColor : "green",
          SNPMouseDownCircleSize : 4,
          SNPMouseDownCircleOpacity : 1.0,
          SNPMouseDownCircleStrokeColor : "#F26223",

     - .. code-block:: javascript

          SNPMouseDownColor : "blue",
          SNPMouseDownCircleSize : 8,
          SNPMouseDownCircleOpacity : 0.5,
          SNPMouseDownCircleStrokeColor : "red",

   * - Image change

     - .. image:: _images/API_main_customize_events_SNP02_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP02_before.html
     
     - .. image:: _images/API_main_customize_events_SNP02_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP02_after.html

::::::::::::::::::::
 Mouse enter
::::::::::::::::::::

- ``SNPMouseEnterDisplay``
    default false, [true/false], open/not open mouse mouse enter event of SNP module

- ``SNPMouseEnterColor``
    default "yellow", "none" means no change, element change color after mouse enter the element

- ``SNPMouseEnterCircleSize``
    default 4, "none" means no change, element change circle size after mouse enter the element.

- ``SNPMouseEnterCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``SNPMouseEnterCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse enter the element.

- ``SNPMouseEnterCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse enter the element.

**Example**: change color, stroke color and  opacity of the circle when mouse enter the element;

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          SNPMouseEnterColor : "yellow",
          SNPMouseEnterCircleOpacity : 1.0,
          SNPMouseEnterCircleStrokeColor : "#F26223",

     - .. code-block:: javascript

          SNPMouseEnterColor : "red",
          SNPMouseEnterCircleOpacity : 0.7,
          SNPMouseEnterCircleStrokeColor : "green",

   * - Image change

     - .. image:: _images/API_main_customize_events_SNP03_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP03_before.html
     
     - .. image:: _images/API_main_customize_events_SNP03_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP03_after.html

::::::::::::::::::::
 Mouse leave
::::::::::::::::::::

- ``SNPMouseLeaveDisplay``
    default false, [true/false], open/not open mouse mouse leave event of SNP module

- ``SNPMouseLeaveColor``
    default "pink", "none" means no change, element change color after mouse leave the element

- ``SNPMouseLeaveCircleSize``
    default 4, "none" means no change, element change circle size after mouse leave the element.

- ``SNPMouseLeaveCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``SNPMouseLeaveCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse leave the element.

- ``SNPMouseLeaveCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse leave the element.

**Example**: change color, size, stroke color and stroke width of the circle when mouse leave the element;

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          SNPMouseLeaveColor : "blue",
          SNPMouseLeaveCircleSize : 4,
          SNPMouseLeaveCircleStrokeColor : "#F26223",
          SNPMouseLeaveCircleStrokeWidth : 1,

     - .. code-block:: javascript

          SNPMouseLeaveColor : "red",
          SNPMouseLeaveCircleSize : 6,
          SNPMouseLeaveCircleStrokeColor : "green",
          SNPMouseLeaveCircleStrokeWidth : 2,

   * - Image change

     - .. image:: _images/API_main_customize_events_SNP04_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP04_before.html
     
     - .. image:: _images/API_main_customize_events_SNP04_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP04_after.html

::::::::::::::::::::
 Mouse move
::::::::::::::::::::

- ``SNPMouseMoveDisplay``
    default false, [true/false], open/not open mouse mouse move event of SNP module

- ``SNPMouseMoveColor``
    default "red", "none" means no change, element change color after mouse move the element

- ``SNPMouseMoveCircleSize``
    default 2, "none" means no change, element change circle size after mouse move the element.

- ``SNPMouseMoveCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse move the element

- ``SNPMouseMoveCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse move the element.

- ``SNPMouseMoveCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse move the element.

**Example**: mouse move event and mouse out event

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After
   
   * - Code change
   
     - .. code-block:: javascript

          SNPMouseMoveColor : "green",
          SNPMouseMoveCircleStrokeColor : "blue",
          SNPMouseMoveCircleStrokeWidth : 3,

     - .. code-block:: javascript

          SNPMouseMoveColor : "red",
          SNPMouseMoveCircleStrokeColor : "#F26223",
          SNPMouseMoveCircleStrokeWidth : 0,
          SNPMouseOutDisplay : true,
          SNPMouseOutAnimationTime : 500,
          SNPMouseOutColor : "none",
          SNPMouseOutCircleSize : "none",
          SNPMouseOutCircleOpacity : 1.0,
          SNPMouseOutCircleStrokeColor : "red",
          SNPMouseOutCircleStrokeWidth : 0,

   * - Image change
   
     - .. image:: _images/API_main_customize_events_SNP05_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP05_before.html
     
     - .. image:: _images/API_main_customize_events_SNP05_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP05_after.html

::::::::::::::::::::
 Mouse out
::::::::::::::::::::

- ``SNPMouseOutDisplay``
    default false, [true/false], open/not open mouse mouse out event of SNP module

- ``SNPMouseOutAnimationTime``
    default 500, animation time after mouse out the element

- ``SNPMouseOutColor``
    default "red", "none" means no change, element change color after mouse out the element

- ``SNPMouseOutCircleSize``
    default 2, "none" means no change, element change circle size after mouse out the element.

- ``SNPMouseOutCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse out the element

- ``SNPMouseOutCircleStrokeColor``
    default "red", "none" means no change, element change stroke color after mouse out the element.

- ``SNPMouseOutCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse out the element.

**Example**: change animation time, size, stroke color and stroke width of the circle when mouse out the element;

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example
   
     - Before
     - After
   
   * - Code change
   
     - .. code-block:: javascript

          SNPMouseOutAnimationTime : 400,
          SNPMouseOutCircleSize : 5,
          SNPMouseOutCircleStrokeColor : "red",
          SNPMouseOutCircleStrokeWidth : 1,

     - .. code-block:: javascript

          SNPMouseOutAnimationTime : 1000,
          SNPMouseOutCircleSize : 5,
          SNPMouseOutCircleStrokeColor : "green",
          SNPMouseOutCircleStrokeWidth : 2,

   * - Image change
   
     - .. image:: _images/API_main_customize_events_SNP06_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP06_before.html
     
     - .. image:: _images/API_main_customize_events_SNP06_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP06_after.html

::::::::::::::::::::
 Mouse up
::::::::::::::::::::

- ``SNPMouseUpDisplay``
    default false, [true/false], open/not open mouse mouse up event of SNP module

- ``SNPMouseUpColor``
    default "grey", "none" means no change, element change color after mouse up the element

- ``SNPMouseUpCircleSize``
    default 4, "none" means no change, element change circle size after mouse up the element.

- ``SNPMouseUpCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse up the element

- ``SNPMouseUpCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse up the element.

- ``SNPMouseUpCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse up the element.

**Example**: change size and color of the circle when mouse up the element;

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          SNPMouseUpColor : "grey",
          SNPMouseUpCircleSize : 4,

     - .. code-block:: javascript

          SNPMouseUpColor : "red",
          SNPMouseUpCircleSize : 6,

   * - Image change

     - .. image:: _images/API_main_customize_events_SNP07_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP07_before.html
     
     - .. image:: _images/API_main_customize_events_SNP07_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP07_after.html

::::::::::::::::::::
 Mouse over
::::::::::::::::::::

- ``SNPMouseOverDisplay``
    default false, [true/false], open/not open mouse mouse Over event of SNP module

- ``SNPMouseOverColor``
    default "red", "none" means no change, element change color after mouse Over the element

- ``SNPMouseOverCircleSize``
    default 2, "none" means no change, element change circle size after mouse Over the element.

- ``SNPMouseOverCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse Over the element

- ``SNPMouseOverCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse Over the element.

- ``SNPMouseOverCircleStrokeWidth``
    default 3, "none" means no change, element change stroke width after mouse Over the element.

**Example**: change size and color of the circle when mouse over the element;

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          SNPMouseOverColor : "red",
          SNPMouseOverCircleSize : 4,

     - .. code-block:: javascript

          SNPMouseOverColor : "none",
          SNPMouseOverCircleSize : "none",

   * - Image change

     - .. image:: _images/API_main_customize_events_SNP08_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP08_before.html
     
     - .. image:: _images/API_main_customize_events_SNP08_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_events_SNP08_after.html

```````````````````
 SCATTER module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in SCATTER module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - SCATTER module
             SCATTERMouseEvent : true,
             SCATTERMouseClickDisplay : false,
             SCATTERMouseClickColor : "red",
             SCATTERMouseClickCircleSize : 4,
             SCATTERMouseClickCircleOpacity : 1.0,
             SCATTERMouseClickCircleStrokeColor : "#F26223",
             SCATTERMouseClickCircleStrokeWidth : 0,
             SCATTERMouseClickTextFromData : "fourth",
             SCATTERMouseClickTextOpacity : 1,
             SCATTERMouseClickTextColor : "red",
             SCATTERMouseClickTextSize : 8,
             SCATTERMouseClickTextPostionX : 1.0,
             SCATTERMouseClickTextPostionY : 10.0,
             SCATTERMouseClickTextDrag : true,
             SCATTERMouseDownDisplay : false,
             SCATTERMouseDownColor : "green",
             SCATTERMouseDownCircleSize : 4,
             SCATTERMouseDownCircleOpacity : 1.0,
             SCATTERMouseDownCircleStrokeColor : "#F26223",
             SCATTERMouseDownCircleStrokeWidth : 0,
             SCATTERMouseEnterDisplay : false,
             SCATTERMouseEnterColor : "yellow",
             SCATTERMouseEnterCircleSize : 4,
             SCATTERMouseEnterCircleOpacity : 1.0,
             SCATTERMouseEnterCircleStrokeColor : "#F26223",
             SCATTERMouseEnterCircleStrokeWidth : 0,
             SCATTERMouseLeaveDisplay : false,
             SCATTERMouseLeaveColor : "pink",
             SCATTERMouseLeaveCircleSize : 4,
             SCATTERMouseLeaveCircleOpacity : 1.0,
             SCATTERMouseLeaveCircleStrokeColor : "#F26223",
             SCATTERMouseLeaveCircleStrokeWidth : 0,
             SCATTERMouseMoveDisplay : false,
             SCATTERMouseMoveColor : "red",
             SCATTERMouseMoveCircleSize : 2,
             SCATTERMouseMoveCircleOpacity : 1.0,
             SCATTERMouseMoveCircleStrokeColor : "#F26223",
             SCATTERMouseMoveCircleStrokeWidth : 0,
             SCATTERMouseOutDisplay : false,
             SCATTERMouseOutAnimationTime : 500,
             SCATTERMouseOutColor : "red",
             SCATTERMouseOutCircleSize : 2,
             SCATTERMouseOutCircleOpacity : 1.0,
             SCATTERMouseOutCircleStrokeColor : "red",
             SCATTERMouseOutCircleStrokeWidth : 0,
             SCATTERMouseUpDisplay : false,
             SCATTERMouseUpColor : "grey",
             SCATTERMouseUpCircleSize : 4,
             SCATTERMouseUpCircleOpacity : 1.0,
             SCATTERMouseUpCircleStrokeColor : "#F26223",
             SCATTERMouseUpCircleStrokeWidth : 0,
             SCATTERMouseOverDisplay : false,
             SCATTERMouseOverColor : "red",
             SCATTERMouseOverCircleSize : 2,
             SCATTERMouseOverCircleOpacity : 1.0,
             SCATTERMouseOverCircleStrokeColor : "#F26223",
             SCATTERMouseOverCircleStrokeWidth : 3,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``SCATTERMouseEvent``
    default true, [true/false], open/not open mouse event of SCATTER module

::::::::::::::::::::
 Mouse click
::::::::::::::::::::

- ``SCATTERMouseClickDisplay``
    default true, [true/false], open/not open mouse click event of SCATTER module

- ``SCATTERMouseClickColor``
    default "red", "none" means no change, element change color after click the element

- ``SCATTERMouseClickCircleSize``
    default 4, "none" means no change, element change circle size after click the element.

- ``SCATTERMouseClickCircleOpacity``
    default 1.0, "none" means no change, element change opacity after click the element

- ``SCATTERMouseClickCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after click the element.

- ``SCATTERMouseClickCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after click the element.

- ``SCATTERMouseClickTextFromData``
    default "fourth", first,second,third,fourth column data click to show 

- ``SCATTERMouseClickTextOpacity``
    default 1.0, text opacity after click the element

- ``SCATTERMouseClickTextColor``
    default "red", text color after click the element

- ``SCATTERMouseClickTextSize``
    default 8, text size after click the element

- ``SCATTERMouseClickTextPostionX``
    default 1.0, text x position after click the element

- ``SCATTERMouseClickTextPostionY``
    default 10.0, text y position after click the element

- ``SCATTERMouseClickTextDrag``
    default true, [true/false], open/not open text drag function

::::::::::::::::::::
 Mouse down
::::::::::::::::::::

- ``SCATTERMouseDownDisplay``
    default false, [true/false], open/not open mouse mouse down event of SCATTER module

- ``SCATTERMouseDownColor``
    default "green", "none" means no change, element change color after mouse down the element

- ``SCATTERMouseDownCircleSize``
    default 4, "none" means no change, element change circle size after mouse down the element.

- ``SCATTERMouseDownCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse down the element

- ``SCATTERMouseDownCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse down the element.

- ``SCATTERMouseDownCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse down the element.

::::::::::::::::::::
 Mouse enter
::::::::::::::::::::

- ``SCATTERMouseEnterDisplay``
    default false, [true/false], open/not open mouse mouse enter event of SCATTER module

- ``SCATTERMouseEnterColor``
    default "yellow", "none" means no change, element change color after mouse enter the element

- ``SCATTERMouseEnterCircleSize``
    default 4, "none" means no change, element change circle size after mouse enter the element.

- ``SCATTERMouseEnterCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``SCATTERMouseEnterCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse enter the element.

- ``SCATTERMouseEnterCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse enter the element.

::::::::::::::::::::
 Mouse leave
::::::::::::::::::::

- ``SCATTERMouseLeaveDisplay``
    default false, [true/false], open/not open mouse mouse leave event of SCATTER module

- ``SCATTERMouseLeaveColor``
    default "pink", "none" means no change, element change color after mouse leave the element

- ``SCATTERMouseLeaveCircleSize``
    default 4, "none" means no change, element change circle size after mouse leave the element.

- ``SCATTERMouseLeaveCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``SCATTERMouseLeaveCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse leave the element.

- ``SCATTERMouseLeaveCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse leave the element.

::::::::::::::::::::
 Mouse move
::::::::::::::::::::

- ``SCATTERMouseMoveDisplay``
    default false, [true/false], open/not open mouse mouse move event of SCATTER module

- ``SCATTERMouseMoveColor``
    default "red", "none" means no change, element change color after mouse move the element

- ``SCATTERMouseMoveCircleSize``
    default 2, "none" means no change, element change circle size after mouse move the element.

- ``SCATTERMouseMoveCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse move the element

- ``SCATTERMouseMoveCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse move the element.

- ``SCATTERMouseMoveCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse move the element.

::::::::::::::::::::
 Mouse out
::::::::::::::::::::

- ``SCATTERMouseOutDisplay``
    default false, [true/false], open/not open mouse mouse out event of SCATTER module

- ``SCATTERMouseOutAnimationTime``
    default 500, animation time after mouse out the element

- ``SCATTERMouseOutColor``
    default "red", "none" means no change, element change color after mouse out the element

- ``SCATTERMouseOutCircleSize``
    default 2, "none" means no change, element change circle size after mouse out the element.

- ``SCATTERMouseOutCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse out the element

- ``SCATTERMouseOutCircleStrokeColor``
    default "red", "none" means no change, element change stroke color after mouse out the element.

- ``SCATTERMouseOutCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse out the element.

::::::::::::::::::::
 Mouse up
::::::::::::::::::::

- ``SCATTERMouseUpDisplay``
    default false, [true/false], open/not open mouse mouse up event of SCATTER module

- ``SCATTERMouseUpColor``
    default "grey", "none" means no change, element change color after mouse up the element

- ``SCATTERMouseUpCircleSize``
    default 4, "none" means no change, element change circle size after mouse up the element.

- ``SCATTERMouseUpCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse up the element

- ``SCATTERMouseUpCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse up the element.

- ``SCATTERMouseUpCircleStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse up the element.

::::::::::::::::::::
 Mouse over
::::::::::::::::::::

- ``SCATTERMouseOverDisplay``
    default false, [true/false], open/not open mouse mouse Over event of SCATTER module

- ``SCATTERMouseOverColor``
    default "red", "none" means no change, element change color after mouse Over the element

- ``SCATTERMouseOverCircleSize``
    default 2, "none" means no change, element change circle size after mouse Over the element.

- ``SCATTERMouseOverCircleOpacity``
    default 1.0, "none" means no change, element change opacity after mouse Over the element

- ``SCATTERMouseOverCircleStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse Over the element.

- ``SCATTERMouseOverCircleStrokeWidth``
    default 3, "none" means no change, element change stroke width after mouse Over the element.

```````````````````
 LINK module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in LINK module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - LINK module
             LINKMouseEvent : true,
             LINKMouseClickDisplay : false,
             LINKMouseClickOpacity : 1.0,
             LINKMouseClickStrokeColor : "green",
             LINKMouseClickStrokeWidth : 4,
             LINKMouseDownDisplay : false,
             LINKMouseDownOpacity : 1.0,
             LINKMouseDownStrokeColor : "#F26223",
             LINKMouseDownStrokeWidth : 4,
             LINKMouseEnterDisplay : false,
             LINKMouseEnterOpacity : 1.0,
             LINKMouseEnterStrokeColor : "#F26223",
             LINKMouseEnterStrokeWidth : 4,
             LINKMouseLeaveDisplay : false,
             LINKMouseLeaveOpacity : 1.0,
             LINKMouseLeaveStrokeColor : "#F26223",
             LINKMouseLeaveStrokeWidth : 4,
             LINKMouseMoveDisplay : false,
             LINKMouseMoveOpacity : 1.0,
             LINKMouseMoveStrokeColor : "#F26223",
             LINKMouseMoveStrokeWidth : 4,
             LINKMouseOutDisplay : false,
             LINKMouseOutAnimationTime : 500,
             LINKMouseOutOpacity : 1.0,
             LINKMouseOutStrokeColor : "red",
             LINKMouseOutStrokeWidth : 4,
             LINKMouseUpDisplay : false,
             LINKMouseUpOpacity : 1.0,
             LINKMouseUpStrokeColor : "#F26223",
             LINKMouseUpStrokeWidth : 4,
             LINKMouseOverDisplay : false,
             LINKMouseOverOpacity : 1.0,
             LINKMouseOverStrokeColor : "#F26223",
             LINKMouseOverStrokeWidth : 3,
             LINKLabelDragEvent : false,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``LINKMouseEvent``
    default true, [true/false], open/not open mouse event of LINK module

::::::::::::::::::::
 Mouse click
::::::::::::::::::::

- ``LINKMouseClickDisplay``
    default true, [true/false], open/not open mouse click event of LINK module

- ``LINKMouseClickOpacity``
    default 1.0, "none" means no change, element change opacity after click the element

- ``LINKMouseClickStrokeColor``
    default "green", "none" means no change, element change color after click the element

- ``LINKMouseClickStrokeWidth``
    default 4, "none" means no change, element change stroke width after click the element.

::::::::::::::::::::
 Mouse down
::::::::::::::::::::

- ``LINKMouseDownDisplay``
    default false, [true/false], open/not open mouse mouse down event of LINK module

- ``LINKMouseDownOpacity``
    default 1.0, "none" means no change, element change opacity after mouse down the element

- ``LINKMouseDownStrokeColor``
    default "#F26223", "none" means no change, element change color after mouse down the element

- ``LINKMouseDownStrokeWidth``
    default 4, "none" means no change, element change stroke width after mouse down the element.

::::::::::::::::::::
 Mouse enter
::::::::::::::::::::

- ``LINKMouseEnterDisplay``
    default false, [true/false], open/not open mouse mouse enter event of LINK module

- ``LINKMouseEnterOpacity``
    default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``LINKMouseEnterStrokeColor``
    default "#F26223", "none" means no change, element change color after mouse enter the element

- ``LINKMouseEnterStrokeWidth``
    default 4, "none" means no change, element change stroke width after mouse enter the element.

::::::::::::::::::::
 Mouse leave
::::::::::::::::::::

- ``LINKMouseLeaveDisplay``
    default false, [true/false], open/not open mouse mouse leave event of LINK module

- ``LINKMouseLeaveOpacity``
    default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``LINKMouseLeaveStrokeColor``
    default "#F26223", "none" means no change, element change color after mouse leave the element

- ``LINKMouseLeaveStrokeWidth``
    default 4, "none" means no change, element change stroke width after mouse leave the element.

::::::::::::::::::::
 Mouse move
::::::::::::::::::::

- ``LINKMouseMoveDisplay``
    default false, [true/false], open/not open mouse mouse move event of LINK module

- ``LINKMouseMoveOpacity``
    default 1.0, "none" means no change, element change opacity after mouse move the element

- ``LINKMouseMoveStrokeColor``
    default "#F26223", "none" means no change, element change color after mouse move the element

- ``LINKMouseMoveStrokeWidth``
    default 4, "none" means no change, element change stroke width after mouse move the element.

::::::::::::::::::::
 Mouse out
::::::::::::::::::::

- ``LINKMouseOutDisplay``
    default false, [true/false], open/not open mouse mouse out event of LINK module

- ``LINKMouseOutAnimationTime``
    default 500, animation time after mouse out the element

- ``LINKMouseOutOpacity``
    default 1.0, "none" means no change, element change opacity after mouse out the element

- ``LINKMouseOutStrokeColor``
    default "red", "none" means no change, element change color after mouse out the element

- ``LINKMouseOutStrokeWidth``
    default 4, "none" means no change, element change stroke width after mouse out the element.

::::::::::::::::::::
 Mouse up
::::::::::::::::::::

- ``LINKMouseUpDisplay``
    default false, [true/false], open/not open mouse mouse up event of LINK module

- ``LINKMouseUpOpacity``
    default 1.0, "none" means no change, element change opacity after mouse up the element

- ``LINKMouseUpStrokeColor``
    default "#F26223", "none" means no change, element change color after mouse up the element

- ``LINKMouseUpStrokeWidth``
    default 4, "none" means no change, element change stroke width after mouse up the element.

::::::::::::::::::::
 Mouse over
::::::::::::::::::::

- ``LINKMouseOverDisplay``
    default true, [true/false], open/not open mouse mouse over event of LINK module

- ``LINKMouseOverOpacity``
    default 1.0, "none" means no change, element change opacity after mouse over the element

- ``LINKMouseOverStrokeColor``
    default "#F26223", "none" means no change, element change color after mouse over the element

- ``LINKMouseOverStrokeWidth``
    default 3, "none" means no change, element change stroke width after mouse over the element.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
 LINK Label Drag Event
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

- ``LINKLabelDragEvent``
    default false, [true/false], open/not open lINK label drag event

```````````````````
 CNV module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in CNV module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - CNV module
             CNVMouseEvent : true,
             CNVMouseClickDisplay : false,
             CNVMouseClickColor : "red",
             CNVMouseClickArcOpacity : 1.0,
             CNVMouseClickArcStrokeColor : "#F26223",
             CNVMouseClickArcStrokeWidth : 0,
             CNVMouseClickTextFromData : "fourth",   //first,second,third,fourth column
             CNVMouseClickTextOpacity : 1,
             CNVMouseClickTextColor : "red",
             CNVMouseClickTextSize : 8,
             CNVMouseClickTextPostionX : 0,
             CNVMouseClickTextPostionY : 0,
             CNVMouseClickTextDrag : true,
             CNVMouseDownDisplay : false,
             CNVMouseDownColor : "green",
             CNVMouseDownArcOpacity : 1.0,
             CNVMouseDownArcStrokeColor : "#F26223",
             CNVMouseDownArcStrokeWidth : 0,
             CNVMouseEnterDisplay : false,
             CNVMouseEnterColor : "yellow",
             CNVMouseEnterArcOpacity : 1.0,
             CNVMouseEnterArcStrokeColor : "#F26223",
             CNVMouseEnterArcStrokeWidth : 0,
             CNVMouseLeaveDisplay : false,
             CNVMouseLeaveColor : "pink",
             CNVMouseLeaveArcOpacity : 1.0,
             CNVMouseLeaveArcStrokeColor : "#F26223",
             CNVMouseLeaveArcStrokeWidth : 0,
             CNVMouseMoveDisplay : false,
             CNVMouseMoveColor : "red",
             CNVMouseMoveArcOpacity : 1.0,
             CNVMouseMoveArcStrokeColor : "#F26223",
             CNVMouseMoveArcStrokeWidth : 0,
             CNVMouseOutDisplay : false,
             CNVMouseOutAnimationTime : 500,
             CNVMouseOutColor : "red",
             CNVMouseOutArcOpacity : 1.0,
             CNVMouseOutArcStrokeColor : "red",
             CNVMouseOutArcStrokeWidth : 0,
             CNVMouseUpDisplay : false,
             CNVMouseUpColor : "grey",
             CNVMouseUpArcOpacity : 1.0,
             CNVMouseUpArcStrokeColor : "#F26223",
             CNVMouseUpArcStrokeWidth : 0,
             CNVMouseOverDisplay : false,
             CNVMouseOverColor : "red",
             CNVMouseOverArcOpacity : 1.0,
             CNVMouseOverArcStrokeColor : "#F26223",
             CNVMouseOverArcStrokeWidth : 3,
             CNVMouseOverTooltipsSetting :"style1",
             CNVMouseOverTooltipsHtml : " ",
             CNVMouseOverTooltipsPosition : "absolute",
             CNVMouseOverTooltipsBackgroundColor : "white",
             CNVMouseOverTooltipsBorderStyle : "solid",
             CNVMouseOverTooltipsBorderWidth : 0,
             CNVMouseOverTooltipsPadding : "3px",
             CNVMouseOverTooltipsBorderRadius : "3px",
             CNVMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``CNVMouseEvent``
    default true, [true/false], open/not open mouse event of CNV module

::::::::::::::::::::
 Mouse click
::::::::::::::::::::

- ``CNVMouseClickDisplay``
    default true, [true/false], open/not open mouse click event of CNV module

- ``CNVMouseClickColor``
    default "red", "none" means no change, element change color after click the element

- ``CNVMouseClickArcOpacity``
    default 1.0, "none" means no change, element change opacity after click the element

- ``CNVMouseClickArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after click the element.

- ``CNVMouseClickArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after click the element.

- ``CNVMouseClickTextFromData``
    default "fourth", first,second,third,fourth column data click to show 

- ``CNVMouseClickTextOpacity``
    default 1.0, text opacity after click the element

- ``CNVMouseClickTextColor``
    default "red", text color after click the element

- ``CNVMouseClickTextSize``
    default 8, text size after click the element

- ``CNVMouseClickTextPostionX``
    default 0, text x position after click the element

- ``CNVMouseClickTextPostionY``
    default 0, text y position after click the element

- ``CNVMouseClickTextDrag``
    default true, [true/false], open/not open text drag function

::::::::::::::::::::
 Mouse down
::::::::::::::::::::

- ``CNVMouseDownDisplay``
    default false, [true/false], open/not open mouse mouse down event of CNV module

- ``CNVMouseDownColor``
    default "green", "none" means no change, element change color after mouse down the element

- ``CNVMouseDownArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse down the element

- ``CNVMouseDownArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse down the element.

- ``CNVMouseDownArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse down the element.

::::::::::::::::::::
 Mouse enter
::::::::::::::::::::

- ``CNVMouseEnterDisplay``
    default false, [true/false], open/not open mouse mouse enter event of CNV module

- ``CNVMouseEnterColor``
    default "yellow", "none" means no change, element change color after mouse enter the element

- ``CNVMouseEnterArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``CNVMouseEnterArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse enter the element.

- ``CNVMouseEnterArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse enter the element.

::::::::::::::::::::
 Mouse leave
::::::::::::::::::::

- ``CNVMouseLeaveDisplay``
    default false, [true/false], open/not open mouse mouse leave event of CNV module

- ``CNVMouseLeaveColor``
    default "pink", "none" means no change, element change color after mouse leave the element

- ``CNVMouseLeaveArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``CNVMouseLeaveArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse leave the element.

- ``CNVMouseLeaveArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse leave the element.

::::::::::::::::::::
 Mouse move
::::::::::::::::::::

- ``CNVMouseMoveDisplay``
    default false, [true/false], open/not open mouse mouse move event of CNV module

- ``CNVMouseMoveColor``
    default "red", "none" means no change, element change color after mouse move the element

- ``CNVMouseMoveArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse move the element

- ``CNVMouseMoveArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse move the element.

- ``CNVMouseMoveArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse move the element.

::::::::::::::::::::
 Mouse out
::::::::::::::::::::

- ``CNVMouseOutDisplay``
    default false, [true/false], open/not open mouse mouse out event of CNV module

- ``CNVMouseOutAnimationTime``
    default 500, animation time after mouse out the element

- ``CNVMouseOutColor``
    default "red", "none" means no change, element change color after mouse out the element

- ``CNVMouseOutArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse out the element

- ``CNVMouseOutArcStrokeColor``
    default "red", "none" means no change, element change stroke color after mouse out the element.

- ``CNVMouseOutArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse out the element.

::::::::::::::::::::
 Mouse up
::::::::::::::::::::

- ``CNVMouseUpDisplay``
    default false, [true/false], open/not open mouse mouse up event of CNV module

- ``CNVMouseUpColor``
    default "grey", "none" means no change, element change color after mouse up the element

- ``CNVMouseUpArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse up the element

- ``CNVMouseUpArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse up the element.

- ``CNVMouseUpArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse up the element.

::::::::::::::::::::
 Mouse over
::::::::::::::::::::

- ``CNVMouseOverDisplay``
    default false, [true/false], open/not open mouse mouse Over event of CNV module

- ``CNVMouseOverColor``
    default "red", "none" means no change, element change color after mouse Over the element

- ``CNVMouseOverArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse Over the element

- ``CNVMouseOverArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse Over the element.

- ``CNVMouseOverArcStrokeWidth``
    default 3, "none" means no change, element change stroke width after mouse Over the element.

```````````````````
 ARC module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in ARC module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - ARC module
             ARCMouseEvent : true,
             ARCMouseClickDisplay : false,
             ARCMouseClickColor : "red",
             ARCMouseClickArcOpacity : 1.0,
             ARCMouseClickArcStrokeColor : "#F26223",
             ARCMouseClickArcStrokeWidth : 1,
             ARCMouseClickTextFromData : "fourth",
             ARCMouseClickTextOpacity : 1,
             ARCMouseClickTextColor : "red",
             ARCMouseClickTextSize : 8,
             ARCMouseClickTextPostionX : 0,
             ARCMouseClickTextPostionY : 0,
             ARCMouseClickTextDrag : true,
             ARCMouseDownDisplay : false,
             ARCMouseDownColor : "green",
             ARCMouseDownArcOpacity : 1.0,
             ARCMouseDownArcStrokeColor : "#F26223",
             ARCMouseDownArcStrokeWidth : 0,
             ARCMouseEnterDisplay : false,
             ARCMouseEnterColor : "yellow",
             ARCMouseEnterArcOpacity : 1.0,
             ARCMouseEnterArcStrokeColor : "#F26223",
             ARCMouseEnterArcStrokeWidth : 0,
             ARCMouseLeaveDisplay : false,
             ARCMouseLeaveColor : "pink",
             ARCMouseLeaveArcOpacity : 1.0,
             ARCMouseLeaveArcStrokeColor : "#F26223",
             ARCMouseLeaveArcStrokeWidth : 0,
             ARCMouseMoveDisplay : false,
             ARCMouseMoveColor : "red",
             ARCMouseMoveArcOpacity : 1.0,
             ARCMouseMoveArcStrokeColor : "#F26223",
             ARCMouseMoveArcStrokeWidth : 0,
             ARCMouseOutDisplay : false,
             ARCMouseOutAnimationTime : 500,
             ARCMouseOutColor : "red",
             ARCMouseOutArcOpacity : 1.0,
             ARCMouseOutArcStrokeColor : "red",
             ARCMouseOutArcStrokeWidth : 0,
             ARCMouseUpDisplay : false,
             ARCMouseUpColor : "grey",
             ARCMouseUpArcOpacity : 1.0,
             ARCMouseUpArcStrokeColor : "#F26223",
             ARCMouseUpArcStrokeWidth : 0,
             ARCMouseOverDisplay : false,
             ARCMouseOverColor : "red",
             ARCMouseOverArcOpacity : 1.0,
             ARCMouseOverArcStrokeColor : "#F26223",
             ARCMouseOverArcStrokeWidth : 3,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``ARCMouseEvent``
    default false, [true/false], open/not open mouse event of ARC module

::::::::::::::::::::
 Mouse click
::::::::::::::::::::

- ``ARCMouseClickDisplay``
    default true, [true/false], open/not open mouse click event of ARC module

- ``ARCMouseClickColor``
    default "red", "none" means no change, element change color after click the element

- ``ARCMouseClickArcOpacity``
    default 1.0, "none" means no change, element change opacity after click the element

- ``ARCMouseClickArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after click the element.

- ``ARCMouseClickArcStrokeWidth``
    default 1, "none" means no change, element change stroke width after click the element.

- ``ARCMouseClickTextFromData``
    default "fourth", first,second,third,fourth column data click to show 

- ``ARCMouseClickTextOpacity``
    default 1.0, text opacity after click the element

- ``ARCMouseClickTextColor``
    default "red", text color after click the element

- ``ARCMouseClickTextSize``
    default 8, text size after click the element

- ``ARCMouseClickTextPostionX``
    default 0, text x position after click the element

- ``ARCMouseClickTextPostionY``
    default 0, text y position after click the element

- ``ARCMouseClickTextDrag``
    default true, [true/false], open/not open text drag function

::::::::::::::::::::
 Mouse down
::::::::::::::::::::

- ``ARCMouseDownDisplay``
    default false, [true/false], open/not open mouse mouse down event of ARC module

- ``ARCMouseDownColor``
    default "green", "none" means no change, element change color after mouse down the element

- ``ARCMouseDownArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse down the element

- ``ARCMouseDownArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse down the element.

- ``ARCMouseDownArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse down the element.

::::::::::::::::::::
 Mouse enter
::::::::::::::::::::

- ``ARCMouseEnterDisplay``
    default false, [true/false], open/not open mouse mouse enter event of ARC module

- ``ARCMouseEnterColor``
    default "yellow", "none" means no change, element change color after mouse enter the element

- ``ARCMouseEnterArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``ARCMouseEnterArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse enter the element.

- ``ARCMouseEnterArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse enter the element.

::::::::::::::::::::
 Mouse leave
::::::::::::::::::::

- ``ARCMouseLeaveDisplay``
    default false, [true/false], open/not open mouse mouse leave event of ARC module

- ``ARCMouseLeaveColor``
    default "pink", "none" means no change, element change color after mouse leave the element

- ``ARCMouseLeaveArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``ARCMouseLeaveArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse leave the element.

- ``ARCMouseLeaveArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse leave the element.

::::::::::::::::::::
 Mouse move
::::::::::::::::::::

- ``ARCMouseMoveDisplay``
    default false, [true/false], open/not open mouse mouse move event of ARC module

- ``ARCMouseMoveColor``
    default "red", "none" means no change, element change color after mouse move the element

- ``ARCMouseMoveArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse move the element

- ``ARCMouseMoveArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse move the element.

- ``ARCMouseMoveArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse move the element.

::::::::::::::::::::
 Mouse out
::::::::::::::::::::

- ``ARCMouseOutDisplay``
    default false, [true/false], open/not open mouse mouse out event of ARC module

- ``ARCMouseOutAnimationTime``
    default 500, animation time after mouse out the element

- ``ARCMouseOutColor``
    default "red", "none" means no change, element change color after mouse out the element

- ``ARCMouseOutArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse out the element

- ``ARCMouseOutArcStrokeColor``
    default "red", "none" means no change, element change stroke color after mouse out the element.

- ``ARCMouseOutArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse out the element.

::::::::::::::::::::
 Mouse up
::::::::::::::::::::

- ``ARCMouseUpDisplay``
    default false, [true/false], open/not open mouse mouse up event of ARC module

- ``ARCMouseUpColor``
    default "grey", "none" means no change, element change color after mouse up the element

- ``ARCMouseUpArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse up the element

- ``ARCMouseUpArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse up the element.

- ``ARCMouseUpArcStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse up the element.

::::::::::::::::::::
 Mouse over
::::::::::::::::::::

- ``ARCMouseOverDisplay``
    default false, [true/false], open/not open mouse mouse Over event of ARC module

- ``ARCMouseOverColor``
    default "red", "none" means no change, element change color after mouse Over the element

- ``ARCMouseOverArcOpacity``
    default 1.0, "none" means no change, element change opacity after mouse Over the element

- ``ARCMouseOverArcStrokeColor``
    default "#F26223", "none" means no change, element change stroke color after mouse Over the element.

- ``ARCMouseOverArcStrokeWidth``
    default 3, "none" means no change, element change stroke width after mouse Over the element.

```````````````````
 HEATMAP module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in HEATMAP module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - HEATMAP module
             HEATMAPMouseEvent : true,
             HEATMAPMouseClickDisplay : false,
             HEATMAPMouseClickColor : "green",            //"none","red"
             HEATMAPMouseClickOpacity : 1.0,            //"none",1.0
             HEATMAPMouseClickStrokeColor : "non   e",  //"none","#F26223"
             HEATMAPMouseClickStrokeWidth : "none",          //"none",3
             HEATMAPMouseDownDisplay : false,
             HEATMAPMouseDownColor : "green",            //"none","red"
             HEATMAPMouseDownOpacity : 1.0,            //"none",1.0
             HEATMAPMouseDownStrokeColor : "none",  //"none","#F26223"
             HEATMAPMouseDownStrokeWidth : "none",          //"none",3
             HEATMAPMouseEnterDisplay : false,
             HEATMAPMouseEnterColor : "green",            //"none","red"
             HEATMAPMouseEnterOpacity : 1.0,            //"none",1.0
             HEATMAPMouseEnterStrokeColor : "none",  //"none","#F26223"
             HEATMAPMouseEnterStrokeWidth : "none",          //"none",3
             HEATMAPMouseLeaveDisplay : false,
             HEATMAPMouseLeaveColor : "green",            //"none","red"
             HEATMAPMouseLeaveOpacity : 1.0,            //"none",1.0
             HEATMAPMouseLeaveStrokeColor : "none",  //"none","#F26223"
             HEATMAPMouseLeaveStrokeWidth : "none",          //"none",3
             HEATMAPMouseMoveDisplay : false,
             HEATMAPMouseMoveColor : "green",            //"none","red"
             HEATMAPMouseMoveOpacity : 1.0,            //"none",1.0
             HEATMAPMouseMoveStrokeColor : "none",  //"none","#F26223"
             HEATMAPMouseMoveStrokeWidth : "none",          //"none",3
             HEATMAPMouseOutDisplay : false,
             HEATMAPMouseOutAnimationTime : 500,
             HEATMAPMouseOutColor : "green",            //"none","red"
             HEATMAPMouseOutOpacity : 1.0,            //"none",1.0
             HEATMAPMouseOutStrokeColor : "none",  //"none","#F26223"
             HEATMAPMouseOutStrokeWidth : "none",          //"none",3
             HEATMAPMouseUpDisplay : false,
             HEATMAPMouseUpColor : "green",            //"none","red"
             HEATMAPMouseUpOpacity : 1.0,            //"none",1.0
             HEATMAPMouseUpStrokeColor : "none",  //"none","#F26223"
             HEATMAPMouseUpStrokeWidth : "none",          //"none",3
             HEATMAPMouseOverDisplay : false,
             HEATMAPMouseOverColor : "none",            //"none","red"
             HEATMAPMouseOverOpacity : 1.0,            //"none",1.0
             HEATMAPMouseOverStrokeColor : "none",  //"none","#F26223"
             HEATMAPMouseOverStrokeWidth : "none",          //"none",3
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``HEATMAPMouseEvent``
    default true, [true/false], open/not open mouse event of HEATMAP module

::::::::::::::::::::
 Mouse click
::::::::::::::::::::

- ``HEATMAPMouseClickDisplay``
    default false, [true/false], open/not open mouse click event of HEATMAP module

- ``HEATMAPMouseClickColor``
    default "green", "none" means no change, element change color after click the element

- ``HEATMAPMouseClickOpacity``
    default 1.0, "none" means no change, element change opacity after click the element

- ``HEATMAPMouseClickStrokeColor``
    default "none", "none" means no change, element change stroke color after click the element.

- ``HEATMAPMouseClickStrokeWidth``
    default "none", "none" means no change, element change stroke width after click the element.

::::::::::::::::::::
 Mouse down
::::::::::::::::::::

- ``HEATMAPMouseDownDisplay``
    default false, [true/false], open/not open mouse mouse down event of HEATMAP module

- ``HEATMAPMouseDownColor``
    default "green", "none" means no change, element change color after mouse down the element

- ``HEATMAPMouseDownOpacity``
    default 1.0, "none" means no change, element change opacity after mouse down the element

- ``HEATMAPMouseDownStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse down the element.

- ``HEATMAPMouseDownStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse down the element.

::::::::::::::::::::
 Mouse enter
::::::::::::::::::::

- ``HEATMAPMouseEnterDisplay``
    default false, [true/false], open/not open mouse mouse enter event of HEATMAP module

- ``HEATMAPMouseEnterColor``
    default "green", "none" means no change, element change color after mouse enter the element

- ``HEATMAPMouseEnterOpacity``
    default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``HEATMAPMouseEnterStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse enter the element.

- ``HEATMAPMouseEnterStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse enter the element.

::::::::::::::::::::
 Mouse leave
::::::::::::::::::::

- ``HEATMAPMouseLeaveDisplay``
    default false, [true/false], open/not open mouse mouse leave event of HEATMAP module

- ``HEATMAPMouseLeaveColor``
    default "green", "none" means no change, element change color after mouse leave the element

- ``HEATMAPMouseLeaveOpacity``
    default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``HEATMAPMouseLeaveStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse leave the element.

- ``HEATMAPMouseLeaveStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse leave the element.

::::::::::::::::::::
 Mouse move
::::::::::::::::::::

- ``HEATMAPMouseMoveDisplay``
    default false, [true/false], open/not open mouse mouse move event of HEATMAP module

- ``HEATMAPMouseMoveColor``
    default "green", "none" means no change, element change color after mouse move the element

- ``HEATMAPMouseMoveOpacity``
    default "none", "none" means no change, element change opacity after mouse move the element

- ``HEATMAPMouseMoveStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse move the element.

- ``HEATMAPMouseMoveStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse move the element.

::::::::::::::::::::
 Mouse out
::::::::::::::::::::

- ``HEATMAPMouseOutDisplay``
    default false, [true/false], open/not open mouse mouse out event of HEATMAP module

- ``HEATMAPMouseOutAnimationTime``
    default 500, animation time after mouse out the element

- ``HEATMAPMouseOutColor``
    default "green", "none" means no change, element change color after mouse out the element

- ``HEATMAPMouseOutOpacity``
    default 1.0, "none" means no change, element change opacity after mouse out the element

- ``HEATMAPMouseOutStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse out the element.

- ``HEATMAPMouseOutStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse out the element.

::::::::::::::::::::
 Mouse up
::::::::::::::::::::

- ``HEATMAPMouseUpDisplay``
    default false, [true/false], open/not open mouse mouse up event of HEATMAP module

- ``HEATMAPMouseUpColor``
    default "green", "none" means no change, element change color after mouse up the element

- ``HEATMAPMouseUpOpacity``
    default 1.0, "none" means no change, element change opacity after mouse up the element

- ``HEATMAPMouseUpStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse up the element.

- ``HEATMAPMouseUpStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse up the element.

::::::::::::::::::::
 Mouse over
::::::::::::::::::::

- ``HEATMAPMouseOverDisplay``
    default true, [true/false], open/not open mouse mouse Over event of HEATMAP module

- ``HEATMAPMouseOverColor``
    default "none", "none" means no change, element change color after mouse Over the element

- ``HEATMAPMouseOverOpacity``
    default 1.0, "none" means no change, element change opacity after mouse Over the element

- ``HEATMAPMouseOverStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse Over the element.

- ``HEATMAPMouseOverStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse Over the element.
   
```````````````````
BUBBLE module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in BUBBLE module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - BUBBLE module
         BUBBLEMouseEvent : true,
         BUBBLEMouseClickDisplay : false,
         BUBBLEMouseClickColor : "green",            //"none","red"
         BUBBLEMouseClickOpacity : 1.0,            //"none",1.0
         BUBBLEMouseClickStrokeColor : "non   e",  //"none","#F26223"
         BUBBLEMouseClickStrokeWidth : "none",          //"none",3
         BUBBLEMouseDownDisplay : false,
         BUBBLEMouseDownColor : "green",            //"none","red"
         BUBBLEMouseDownOpacity : 1.0,            //"none",1.0
         BUBBLEMouseDownStrokeColor : "none",  //"none","#F26223"
         BUBBLEMouseDownStrokeWidth : "none",          //"none",3
         BUBBLEMouseEnterDisplay : false,
         BUBBLEMouseEnterColor : "green",            //"none","red"
         BUBBLEMouseEnterOpacity : 1.0,            //"none",1.0
         BUBBLEMouseEnterStrokeColor : "none",  //"none","#F26223"
         BUBBLEMouseEnterStrokeWidth : "none",          //"none",3
         BUBBLEMouseLeaveDisplay : false,
         BUBBLEMouseLeaveColor : "green",            //"none","red"
         BUBBLEMouseLeaveOpacity : 1.0,            //"none",1.0
         BUBBLEMouseLeaveStrokeColor : "none",  //"none","#F26223"
         BUBBLEMouseLeaveStrokeWidth : "none",          //"none",3
         BUBBLEMouseMoveDisplay : false,
         BUBBLEMouseMoveColor : "green",            //"none","red"
         BUBBLEMouseMoveOpacity : 1.0,            //"none",1.0
         BUBBLEMouseMoveStrokeColor : "none",  //"none","#F26223"
         BUBBLEMouseMoveStrokeWidth : "none",          //"none",3
         BUBBLEMouseOutDisplay : false,
         BUBBLEMouseOutAnimationTime : 500,
         BUBBLEMouseOutColor : "green",            //"none","red"
         BUBBLEMouseOutOpacity : 1.0,            //"none",1.0
         BUBBLEMouseOutStrokeColor : "none",  //"none","#F26223"
         BUBBLEMouseOutStrokeWidth : "none",          //"none",3
         BUBBLEMouseUpDisplay : false,
         BUBBLEMouseUpColor : "green",            //"none","red"
         BUBBLEMouseUpOpacity : 1.0,            //"none",1.0
         BUBBLEMouseUpStrokeColor : "none",  //"none","#F26223"
         BUBBLEMouseUpStrokeWidth : "none",          //"none",3
         BUBBLEMouseOverDisplay : false,
         BUBBLEMouseOverColor : "none",            //"none","red"
         BUBBLEMouseOverOpacity : 1.0,            //"none",1.0
         BUBBLEMouseOverStrokeColor : "none",  //"none","#F26223"
         BUBBLEMouseOverStrokeWidth : "none",          //"none",3
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``BUBBLEMouseEvent``
   default true, [true/false], open/not open mouse event of BUBBLE module

::::::::::::::::::::
Mouse click
::::::::::::::::::::

- ``BUBBLEMouseClickDisplay``
   default false, [true/false], open/not open mouse click event of BUBBLE module

- ``BUBBLEMouseClickColor``
   default "green", "none" means no change, element change color after click the element

- ``BUBBLEMouseClickOpacity``
   default 1.0, "none" means no change, element change opacity after click the element

- ``BUBBLEMouseClickStrokeColor``
   default "none", "none" means no change, element change stroke color after click the element.

- ``BUBBLEMouseClickStrokeWidth``
   default "none", "none" means no change, element change stroke width after click the element.

::::::::::::::::::::
Mouse down
::::::::::::::::::::

- ``BUBBLEMouseDownDisplay``
   default false, [true/false], open/not open mouse mouse down event of BUBBLE module

- ``BUBBLEMouseDownColor``
   default "green", "none" means no change, element change color after mouse down the element

- ``BUBBLEMouseDownOpacity``
   default 1.0, "none" means no change, element change opacity after mouse down the element

- ``BUBBLEMouseDownStrokeColor``
   default "none", "none" means no change, element change stroke color after mouse down the element.

- ``BUBBLEMouseDownStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse down the element.

::::::::::::::::::::
Mouse enter
::::::::::::::::::::

- ``BUBBLEMouseEnterDisplay``
   default false, [true/false], open/not open mouse mouse enter event of BUBBLE module

- ``BUBBLEMouseEnterColor``
   default "green", "none" means no change, element change color after mouse enter the element

- ``BUBBLEMouseEnterOpacity``
   default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``BUBBLEMouseEnterStrokeColor``
   default "none", "none" means no change, element change stroke color after mouse enter the element.

- ``BUBBLEMouseEnterStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse enter the element.

::::::::::::::::::::
Mouse leave
::::::::::::::::::::

- ``BUBBLEMouseLeaveDisplay``
   default false, [true/false], open/not open mouse mouse leave event of BUBBLE module

- ``BUBBLEMouseLeaveColor``
   default "green", "none" means no change, element change color after mouse leave the element

- ``BUBBLEMouseLeaveOpacity``
   default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``BUBBLEMouseLeaveStrokeColor``
   default "none", "none" means no change, element change stroke color after mouse leave the element.

- ``BUBBLEMouseLeaveStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse leave the element.

::::::::::::::::::::
Mouse move
::::::::::::::::::::

- ``BUBBLEMouseMoveDisplay``
   default false, [true/false], open/not open mouse mouse move event of BUBBLE module

- ``BUBBLEMouseMoveColor``
   default "green", "none" means no change, element change color after mouse move the element

- ``BUBBLEMouseMoveOpacity``
   default "none", "none" means no change, element change opacity after mouse move the element

- ``BUBBLEMouseMoveStrokeColor``
   default "none", "none" means no change, element change stroke color after mouse move the element.

- ``BUBBLEMouseMoveStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse move the element.

::::::::::::::::::::
Mouse out
::::::::::::::::::::

- ``BUBBLEMouseOutDisplay``
   default false, [true/false], open/not open mouse mouse out event of BUBBLE module

- ``BUBBLEMouseOutAnimationTime``
   default 500, animation time after mouse out the element

- ``BUBBLEMouseOutColor``
   default "green", "none" means no change, element change color after mouse out the element

- ``BUBBLEMouseOutOpacity``
   default 1.0, "none" means no change, element change opacity after mouse out the element

- ``BUBBLEMouseOutStrokeColor``
   default "none", "none" means no change, element change stroke color after mouse out the element.

- ``BUBBLEMouseOutStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse out the element.

::::::::::::::::::::
Mouse up
::::::::::::::::::::

- ``BUBBLEMouseUpDisplay``
   default false, [true/false], open/not open mouse mouse up event of BUBBLE module

- ``BUBBLEMouseUpColor``
   default "green", "none" means no change, element change color after mouse up the element

- ``BUBBLEMouseUpOpacity``
   default 1.0, "none" means no change, element change opacity after mouse up the element

- ``BUBBLEMouseUpStrokeColor``
   default "none", "none" means no change, element change stroke color after mouse up the element.

- ``BUBBLEMouseUpStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse up the element.

::::::::::::::::::::
Mouse over
::::::::::::::::::::

- ``BUBBLEMouseOverDisplay``
   default true, [true/false], open/not open mouse mouse Over event of BUBBLE module

- ``BUBBLEMouseOverColor``
   default "none", "none" means no change, element change color after mouse Over the element

- ``BUBBLEMouseOverOpacity``
   default 1.0, "none" means no change, element change opacity after mouse Over the element

- ``BUBBLEMouseOverStrokeColor``
   default "none", "none" means no change, element change stroke color after mouse Over the element.

- ``BUBBLEMouseOverStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse Over the element.   


```````````````````
 HISTOGRAM module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in HISTOGRAM module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - HISTOGRAM module
             HISTOGRAMMouseEvent : true,
             HISTOGRAMMouseClickDisplay : false,
             HISTOGRAMMouseClickColor : "red",            //"none","red"
             HISTOGRAMMouseClickOpacity : 1.0,            //"none",1.0
             HISTOGRAMMouseClickStrokeColor : "none",  //"none","#F26223"
             HISTOGRAMMouseClickStrokeWidth : "none",          //"none",3
             HISTOGRAMMouseDownDisplay : false,
             HISTOGRAMMouseDownColor : "red",            //"none","red"
             HISTOGRAMMouseDownOpacity : 1.0,            //"none",1.0
             HISTOGRAMMouseDownStrokeColor : "none",  //"none","#F26223"
             HISTOGRAMMouseDownStrokeWidth : "none",          //"none",3
             HISTOGRAMMouseEnterDisplay : false,
             HISTOGRAMMouseEnterColor : "red",            //"none","red"
             HISTOGRAMMouseEnterOpacity : 1.0,            //"none",1.0
             HISTOGRAMMouseEnterStrokeColor : "none",  //"none","#F26223"
             HISTOGRAMMouseEnterStrokeWidth : "none",          //"none",3
             HISTOGRAMMouseLeaveDisplay : false,
             HISTOGRAMMouseLeaveColor : "red",            //"none","red"
             HISTOGRAMMouseLeaveOpacity : 1.0,            //"none",1.0
             HISTOGRAMMouseLeaveStrokeColor : "none",  //"none","#F26223"
             HISTOGRAMMouseLeaveStrokeWidth : "none",          //"none",3
             HISTOGRAMMouseMoveDisplay : false,
             HISTOGRAMMouseMoveColor : "red",            //"none","red"
             HISTOGRAMMouseMoveOpacity : 1.0,            //"none",1.0
             HISTOGRAMMouseMoveStrokeColor : "none",  //"none","#F26223"
             HISTOGRAMMouseMoveStrokeWidth : "none",          //"none",3
             HISTOGRAMMouseOutDisplay : false,
             HISTOGRAMMouseOutAnimationTime : 500,
             HISTOGRAMMouseOutColor : "red",            //"none","red"
             HISTOGRAMMouseOutOpacity : 1.0,            //"none",1.0
             HISTOGRAMMouseOutStrokeColor : "none",  //"none","#F26223"
             HISTOGRAMMouseOutStrokeWidth : "none",          //"none",3
             HISTOGRAMMouseUpDisplay : false,
             HISTOGRAMMouseUpColor : "red",            //"none","red"
             HISTOGRAMMouseUpOpacity : 1.0,            //"none",1.0
             HISTOGRAMMouseUpStrokeColor : "none",  //"none","#F26223"
             HISTOGRAMMouseUpStrokeWidth : "none",          //"none",3
             HISTOGRAMMouseOverDisplay : false,
             HISTOGRAMMouseOverColor : "red",            //"none","red"
             HISTOGRAMMouseOverOpacity : 1.0,            //"none",1.0
             HISTOGRAMMouseOverStrokeColor : "none",  //"none","#F26223"
             HISTOGRAMMouseOverStrokeWidth : "none",          //"none",3
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``HISTOGRAMMouseEvent``
    default true, [true/false], open/not open mouse event of HISTOGRAM module

::::::::::::::::::::
 Mouse click
::::::::::::::::::::

- ``HISTOGRAMMouseClickDisplay``
    default false, [true/false], open/not open mouse click event of HISTOGRAM module

- ``HISTOGRAMMouseClickColor``
    default "red", "none" means no change, element change color after click the element

- ``HISTOGRAMMouseClickOpacity``
    default 1.0, "none" means no change, element change opacity after click the element

- ``HISTOGRAMMouseClickStrokeColor``
    default "none", "none" means no change, element change stroke color after click the element.

- ``HISTOGRAMMouseClickStrokeWidth``
    default "none", "none" means no change, element change stroke width after click the element.

::::::::::::::::::::
 Mouse down
::::::::::::::::::::

- ``HISTOGRAMMouseDownDisplay``
    default false, [true/false], open/not open mouse mouse down event of HISTOGRAM module

- ``HISTOGRAMMouseDownColor``
    default "red", "none" means no change, element change color after mouse down the element

- ``HISTOGRAMMouseDownOpacity``
    default 1.0, "none" means no change, element change opacity after mouse down the element

- ``HISTOGRAMMouseDownStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse down the element.

- ``HISTOGRAMMouseDownStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse down the element.

::::::::::::::::::::
 Mouse enter
::::::::::::::::::::

- ``HISTOGRAMMouseEnterDisplay``
    default false, [true/false], open/not open mouse mouse enter event of HISTOGRAM module

- ``HISTOGRAMMouseEnterColor``
    default "red", "none" means no change, element change color after mouse enter the element

- ``HISTOGRAMMouseEnterOpacity``
    default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``HISTOGRAMMouseEnterStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse enter the element.

- ``HISTOGRAMMouseEnterStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse enter the element.

::::::::::::::::::::
 Mouse leave
::::::::::::::::::::

- ``HISTOGRAMMouseLeaveDisplay``
    default false, [true/false], open/not open mouse mouse leave event of HISTOGRAM module

- ``HISTOGRAMMouseLeaveColor``
    default "red", "none" means no change, element change color after mouse leave the element

- ``HISTOGRAMMouseLeaveOpacity``
    default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``HISTOGRAMMouseLeaveStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse leave the element.

- ``HISTOGRAMMouseLeaveStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse leave the element.

::::::::::::::::::::
 Mouse move
::::::::::::::::::::

- ``HISTOGRAMMouseMoveDisplay``
    default false, [true/false], open/not open mouse mouse move event of HISTOGRAM module

- ``HISTOGRAMMouseMoveColor``
    default "red", "none" means no change, element change color after mouse move the element

- ``HISTOGRAMMouseMoveOpacity``
    default 1.0, "none" means no change, element change opacity after mouse move the element

- ``HISTOGRAMMouseMoveStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse move the element.

- ``HISTOGRAMMouseMoveStrokeWidth``
    default 0, "none" means no change, element change stroke width after mouse move the element.

::::::::::::::::::::
 Mouse out
::::::::::::::::::::

- ``HISTOGRAMMouseOutDisplay``
    default false, [true/false], open/not open mouse mouse out event of HISTOGRAM module

- ``HISTOGRAMMouseOutAnimationTime``
    default 500, animation time after mouse out the element

- ``HISTOGRAMMouseOutColor``
    default "red", "none" means no change, element change color after mouse out the element

- ``HISTOGRAMMouseOutOpacity``
    default 1.0, "none" means no change, element change opacity after mouse out the element

- ``HISTOGRAMMouseOutStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse out the element.

- ``HISTOGRAMMouseOutStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse out the element.

::::::::::::::::::::
 Mouse up
::::::::::::::::::::

- ``HISTOGRAMMouseUpDisplay``
    default false, [true/false], open/not open mouse mouse up event of HISTOGRAM module

- ``HISTOGRAMMouseUpColor``
    default "red", "none" means no change, element change color after mouse up the element

- ``HISTOGRAMMouseUpOpacity``
    default 1.0, "none" means no change, element change opacity after mouse up the element

- ``HISTOGRAMMouseUpStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse up the element.

- ``HISTOGRAMMouseUpStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse up the element.

::::::::::::::::::::
 Mouse over
::::::::::::::::::::

- ``HISTOGRAMMouseOverDisplay``
    default true, [true/false], open/not open mouse mouse Over event of HISTOGRAM module

- ``HISTOGRAMMouseOverColor``
    default "red", "none" means no change, element change color after mouse Over the element

- ``HISTOGRAMMouseOverOpacity``
    default 1.0, "none" means no change, element change opacity after mouse Over the element

- ``HISTOGRAMMouseOverStrokeColor``
    default "none", "none" means no change, element change stroke color after mouse Over the element.

- ``HISTOGRAMMouseOverStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse Over the element.

```````````````````
 LINE module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in LINE module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - LINE module
             LINEMouseEvent : true,
             LINEMouseClickDisplay : false,
             LINEMouseClickLineOpacity : 1,           //"none"
             LINEMouseClickLineStrokeColor : "red",   //"none"
             LINEMouseClickLineStrokeWidth : "none",  //"none"
             LINEMouseDownDisplay : false,
             LINEMouseDownLineOpacity : 1,           //"none"
             LINEMouseDownLineStrokeColor : "red",   //"none"
             LINEMouseDownLineStrokeWidth : "none",  //"none"
             LINEMouseEnterDisplay : false,
             LINEMouseEnterLineOpacity : 1,           //"none"
             LINEMouseEnterLineStrokeColor : "red",   //"none"
             LINEMouseEnterLineStrokeWidth : "none",  //"none"
             LINEMouseLeaveDisplay : false,
             LINEMouseLeaveLineOpacity : 1,           //"none"
             LINEMouseLeaveLineStrokeColor : "red",   //"none"
             LINEMouseLeaveLineStrokeWidth : "none",  //"none"
             LINEMouseMoveDisplay : false,
             LINEMouseMoveLineOpacity : 1,           //"none"
             LINEMouseMoveLineStrokeColor : "red",   //"none"
             LINEMouseMoveLineStrokeWidth : "none",  //"none"
             LINEMouseOutDisplay : false,
             LINEMouseOutAnimationTime : 500,
             LINEMouseOutLineOpacity : 1.0,   //"none"
             LINEMouseOutLineStrokeColor : "red",    //"none"
             LINEMouseOutLineStrokeWidth : "none",    //"none"
             LINEMouseUpDisplay : false,
             LINEMouseUpLineOpacity : 1,           //"none"
             LINEMouseUpLineStrokeColor : "red",   //"none"
             LINEMouseUpLineStrokeWidth : "none",  //"none"
             LINEMouseOverDisplay : false,
             LINEMouseOverLineOpacity : 1,           //"none"
             LINEMouseOverLineStrokeColor : "red",   //"none"
             LINEMouseOverLineStrokeWidth : "none",  //"none"
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``LINEMouseEvent``
    default true, [true/false], open/not open mouse event of LINE module

::::::::::::::::::::
 Mouse click
::::::::::::::::::::

- ``LINEMouseClickDisplay``
    default false, [true/false], open/not open mouse click event of LINE module

- ``LINEMouseClickLineOpacity``
    default 1.0, "none" means no change, element change opacity after click the element

- ``LINEMouseClickLineStrokeColor``
    default "red", "none" means no change, element change stroke color after click the element.

- ``LINEMouseClickLineStrokeWidth``
    default "none", "none" means no change, element change stroke width after click the element.

::::::::::::::::::::
 Mouse down
::::::::::::::::::::

- ``LINEMouseDownDisplay``
    default false, [true/false], open/not open mouse mouse down event of LINE module

- ``LINEMouseDownLineOpacity``
    default 1.0, "none" means no change, element change opacity after mouse down the element

- ``LINEMouseDownLineStrokeColor``
    default "red", "none" means no change, element change stroke color after mouse down the element.

- ``LINEMouseDownLineStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse down the element.

::::::::::::::::::::
 Mouse enter
::::::::::::::::::::

- ``LINEMouseEnterDisplay``
    default false, [true/false], open/not open mouse mouse enter event of LINE module

- ``LINEMouseEnterLineOpacity``
    default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``LINEMouseEnterLineStrokeColor``
    default "red", "none" means no change, element change stroke color after mouse enter the element.

- ``LINEMouseEnterLineStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse enter the element.

::::::::::::::::::::
 Mouse leave
::::::::::::::::::::

- ``LINEMouseLeaveDisplay``
    default false, [true/false], open/not open mouse mouse leave event of LINE module

- ``LINEMouseLeaveLineOpacity``
    default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``LINEMouseLeaveLineStrokeColor``
    default "red", "none" means no change, element change stroke color after mouse leave the element.

- ``LINEMouseLeaveLineStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse leave the element.

::::::::::::::::::::
 Mouse move
::::::::::::::::::::

- ``LINEMouseMoveDisplay``
    default false, [true/false], open/not open mouse mouse move event of LINE module

- ``LINEMouseMoveLineOpacity``
    default 1.0, "none" means no change, element change opacity after mouse move the element

- ``LINEMouseMoveLineStrokeColor``
    default "red", "none" means no change, element change stroke color after mouse move the element.

- ``LINEMouseMoveLineStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse move the element.

::::::::::::::::::::
 Mouse out
::::::::::::::::::::

- ``LINEMouseOutDisplay``
    default false, [true/false], open/not open mouse mouse out event of LINE module

- ``LINEMouseOutAnimationTime``
    default 500, animation time after mouse out the element

- ``LINEMouseOutLineOpacity``
    default 1.0, "none" means no change, element change opacity after mouse out the element

- ``LINEMouseOutLineStrokeColor``
    default "red", "none" means no change, element change stroke color after mouse out the element.

- ``LINEMouseOutLineStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse out the element.

::::::::::::::::::::
 Mouse up
::::::::::::::::::::

- ``LINEMouseUpDisplay``
    default false, [true/false], open/not open mouse mouse up event of LINE module

- ``LINEMouseUpLineOpacity``
    default 1.0, "none" means no change, element change opacity after mouse up the element

- ``LINEMouseUpLineStrokeColor``
    default "red", "none" means no change, element change stroke color after mouse up the element.

- ``LINEMouseUpLineStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse up the element.

::::::::::::::::::::
 Mouse over
::::::::::::::::::::

- ``LINEMouseOverDisplay``
    default false, [true/false], open/not open mouse mouse Over event of LINE module

- ``LINEMouseOverLineOpacity``
    default 1.0, "none" means no change, element change opacity after mouse Over the element

- ``LINEMouseOverLineStrokeColor``
    default "red", "none" means no change, element change stroke color after mouse Over the element.

- ``LINEMouseOverLineStrokeWidth``
    default "none", "none" means no change, element change stroke width after mouse Over the element.
   
```````````````````
WIG module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in WIG module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - WIG module
         WIGMouseEvent : true,
         WIGMouseClickDisplay : false,
         WIGMouseClickLineOpacity : 1,           //"none"
         WIGMouseClickLineStrokeColor : "red",   //"none"
         WIGMouseClickLineStrokeWidth : "none",  //"none"
         WIGMouseClickFillColor :"none",
         WIGMouseDownDisplay : false,
         WIGMouseDownLineOpacity : 1,           //"none"
         WIGMouseDownLineStrokeColor : "red",   //"none"
         WIGMouseDownLineStrokeWidth : "none",  //"none"
         WIGMouseDownFillColor :"none",
         WIGMouseEnterDisplay : false,
         WIGMouseEnterLineOpacity : 1,           //"none"
         WIGMouseEnterLineStrokeColor : "red",   //"none"
         WIGMouseEnterLineStrokeWidth : "none",  //"none"
         WIGMouseEnterFillColor :"none",
         WIGMouseLeaveDisplay : false,
         WIGMouseLeaveLineOpacity : 1,           //"none"
         WIGMouseLeaveLineStrokeColor : "red",   //"none"
         WIGMouseLeaveLineStrokeWidth : "none",  //"none"
         WIGMouseLeaveFillColor :"none",
         WIGMouseMoveDisplay : false,
         WIGMouseMoveLineOpacity : 1,           //"none"
         WIGMouseMoveLineStrokeColor : "red",   //"none"
         WIGMouseMoveLineStrokeWidth : "none",  //"none"
         WIGMouseMoveFillColor :"none",
         WIGMouseOutDisplay : false,
         WIGMouseOutAnimationTime : 500,
         WIGMouseOutLineOpacity : 1.0,   //"none"
         WIGMouseOutLineStrokeColor : "red",    //"none"
         WIGMouseOutLineStrokeWidth : "none",    //"none"
         WIGMouseOutFillColor :"none",
         WIGMouseUpDisplay : false,
         WIGMouseUpLineOpacity : 1,           //"none"
         WIGMouseUpLineStrokeColor : "red",   //"none"
         WIGMouseUpLineStrokeWidth : "none",  //"none"
         WIGMouseUpFillColor :"none",
         WIGMouseOverDisplay : false,
         WIGMouseOverLineOpacity : 1,           //"none"
         WIGMouseOverLineStrokeColor : "red",   //"none"
         WIGMouseOverLineStrokeWidth : "none",  //"none"
         WIGMouseOverFillColor :"none",
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``WIGMouseEvent``
   default true, [true/false], open/not open mouse event of WIG module

::::::::::::::::::::
Mouse click
::::::::::::::::::::

- ``WIGMouseClickDisplay``
   default false, [true/false], open/not open mouse click event of WIG module

- ``WIGMouseClickLineOpacity``
   default 1.0, "none" means no change, element change opacity after click the element

- ``WIGMouseClickLineStrokeColor``
   default "red", "none" means no change, element change stroke color after click the element.

- ``WIGMouseClickLineStrokeWidth``
   default "none", "none" means no change, element change stroke width after click the element.
   
- ``WIGMouseClickFillColor``
   default "none", "none" means no change, element change fill color after click the element.

::::::::::::::::::::
Mouse down
::::::::::::::::::::

- ``WIGMouseDownDisplay``
   default false, [true/false], open/not open mouse mouse down event of WIG module

- ``WIGMouseDownLineOpacity``
   default 1.0, "none" means no change, element change opacity after mouse down the element

- ``WIGMouseDownLineStrokeColor``
   default "red", "none" means no change, element change stroke color after mouse down the element.

- ``WIGMouseDownLineStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse down the element.

- ``WIGMouseDownFillColor``
   default "none", "none" means no change, element change fill color after mouse down the element.

::::::::::::::::::::
Mouse enter
::::::::::::::::::::

- ``WIGMouseEnterDisplay``
   default false, [true/false], open/not open mouse mouse enter event of WIG module

- ``WIGMouseEnterLineOpacity``
   default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``WIGMouseEnterLineStrokeColor``
   default "red", "none" means no change, element change stroke color after mouse enter the element.

- ``WIGMouseEnterLineStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse enter the element.
   
- ``WIGMouseEnterFillColor``
   default "none", "none" means no change, element change fill color after mouse enter the element.

::::::::::::::::::::
Mouse leave
::::::::::::::::::::

- ``WIGMouseLeaveDisplay``
   default false, [true/false], open/not open mouse mouse leave event of WIG module

- ``WIGMouseLeaveLineOpacity``
   default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``WIGMouseLeaveLineStrokeColor``
   default "red", "none" means no change, element change stroke color after mouse leave the element.

- ``WIGMouseLeaveLineStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse leave the element.

- ``WIGMouseLeaveFillColor``
   default "none", "none" means no change, element change fill color after mouse leave the element.

::::::::::::::::::::
Mouse move
::::::::::::::::::::

- ``WIGMouseMoveDisplay``
   default false, [true/false], open/not open mouse mouse move event of WIG module

- ``WIGMouseMoveLineOpacity``
   default 1.0, "none" means no change, element change opacity after mouse move the element

- ``WIGMouseMoveLineStrokeColor``
   default "red", "none" means no change, element change stroke color after mouse move the element.

- ``WIGMouseMoveLineStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse move the element.

- ``WIGMouseMoveFillColor``
   default "none", "none" means no change, element change fill color after mouse move the element.

::::::::::::::::::::
Mouse out
::::::::::::::::::::

- ``WIGMouseOutDisplay``
   default false, [true/false], open/not open mouse mouse out event of WIG module

- ``WIGMouseOutAnimationTime``
   default 500, animation time after mouse out the element

- ``WIGMouseOutLineOpacity``
   default 1.0, "none" means no change, element change opacity after mouse out the element

- ``WIGMouseOutLineStrokeColor``
   default "red", "none" means no change, element change stroke color after mouse out the element.

- ``WIGMouseOutLineStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse out the element.

- ``WIGMouseOutFillColor``
   default "none", "none" means no change, element change fill color after mouse out the element.

::::::::::::::::::::
Mouse up
::::::::::::::::::::

- ``WIGMouseUpDisplay``
   default false, [true/false], open/not open mouse mouse up event of WIG module

- ``WIGMouseUpLineOpacity``
   default 1.0, "none" means no change, element change opacity after mouse up the element

- ``WIGMouseUpLineStrokeColor``
   default "red", "none" means no change, element change stroke color after mouse up the element.

- ``WIGMouseUpLineStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse up the element.

- ``WIGMouseUpFillColor``
   default "none", "none" means no change, element change fill color after mouse up the element.

::::::::::::::::::::
Mouse over
::::::::::::::::::::

- ``WIGMouseOverDisplay``
   default false, [true/false], open/not open mouse mouse Over event of WIG module

- ``WIGMouseOverLineOpacity``
   default 1.0, "none" means no change, element change opacity after mouse Over the element

- ``WIGMouseOverLineStrokeColor``
   default "red", "none" means no change, element change stroke color after mouse Over the element.

- ``WIGMouseOverLineStrokeWidth``
   default "none", "none" means no change, element change stroke width after mouse Over the element.

- ``WIGMouseOverFillColor``
   default "none", "none" means no change, element change fill color after mouse over the element.

```````````````````
LOLLIPOP module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in LOLLIPOP module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - LOLLIPOP module
         LOLLIPOPMouseEvent : true,
         LOLLIPOPMouseClickDisplay : false,
         LOLLIPOPMouseClickColor : "red",
         LOLLIPOPMouseClickCircleSize : 4,
         LOLLIPOPMouseClickCircleOpacity : 1.0,
         LOLLIPOPMouseClickCircleStrokeColor : "#F26223",
         LOLLIPOPMouseClickCircleStrokeWidth : 0,
         LOLLIPOPMouseClickTextFromData : "fourth",
         LOLLIPOPMouseClickTextOpacity : 1,
         LOLLIPOPMouseClickTextColor : "red",
         LOLLIPOPMouseClickTextSize : 8,
         LOLLIPOPMouseClickTextPostionX : 1.0,
         LOLLIPOPMouseClickTextPostionY : 10.0,
         LOLLIPOPMouseClickTextDrag : true,
         LOLLIPOPMouseDownDisplay : false,
         LOLLIPOPMouseDownColor : "green",
         LOLLIPOPMouseDownCircleSize : 4,
         LOLLIPOPMouseDownCircleOpacity : 1.0,
         LOLLIPOPMouseDownCircleStrokeColor : "#F26223",
         LOLLIPOPMouseDownCircleStrokeWidth : 0,
         LOLLIPOPMouseEnterDisplay : false,
         LOLLIPOPMouseEnterColor : "yellow",
         LOLLIPOPMouseEnterCircleSize : 4,
         LOLLIPOPMouseEnterCircleOpacity : 1.0,
         LOLLIPOPMouseEnterCircleStrokeColor : "#F26223",
         LOLLIPOPMouseEnterCircleStrokeWidth : 0,
         LOLLIPOPMouseLeaveDisplay : false,
         LOLLIPOPMouseLeaveColor : "pink",
         LOLLIPOPMouseLeaveCircleSize : 4,
         LOLLIPOPMouseLeaveCircleOpacity : 1.0,
         LOLLIPOPMouseLeaveCircleStrokeColor : "#F26223",
         LOLLIPOPMouseLeaveCircleStrokeWidth : 0,
         LOLLIPOPMouseMoveDisplay : false,
         LOLLIPOPMouseMoveColor : "red",
         LOLLIPOPMouseMoveCircleSize : 2,
         LOLLIPOPMouseMoveCircleOpacity : 1.0,
         LOLLIPOPMouseMoveCircleStrokeColor : "#F26223",
         LOLLIPOPMouseMoveCircleStrokeWidth : 0,
         LOLLIPOPMouseOutDisplay : false,
         LOLLIPOPMouseOutAnimationTime : 500,
         LOLLIPOPMouseOutColor : "red",
         LOLLIPOPMouseOutCircleSize : 2,
         LOLLIPOPMouseOutCircleOpacity : 1.0,
         LOLLIPOPMouseOutCircleStrokeColor : "red",
         LOLLIPOPMouseOutCircleStrokeWidth : 0,
         LOLLIPOPMouseUpDisplay : false,
         LOLLIPOPMouseUpColor : "grey",
         LOLLIPOPMouseUpCircleSize : 4,
         LOLLIPOPMouseUpCircleOpacity : 1.0,
         LOLLIPOPMouseUpCircleStrokeColor : "#F26223",
         LOLLIPOPMouseUpCircleStrokeWidth : 0,
         LOLLIPOPMouseOverDisplay : false,
         LOLLIPOPMouseOverColor : "red",
         LOLLIPOPMouseOverCircleSize : 2,
         LOLLIPOPMouseOverCircleOpacity : 1.0,
         LOLLIPOPMouseOverCircleStrokeColor : "#F26223",
         LOLLIPOPMouseOverCircleStrokeWidth : 3,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``LOLLIPOPMouseEvent``
   default true, [true/false], open/not open mouse event of LOLLIPOP module

::::::::::::::::::::
Mouse click
::::::::::::::::::::

- ``LOLLIPOPMouseClickDisplay``
   default true, [true/false], open/not open mouse click event of LOLLIPOP module

- ``LOLLIPOPMouseClickColor``
   default "red", "none" means no change, element change color after click the element

- ``LOLLIPOPMouseClickCircleSize``
   default 4, "none" means no change, element change circle size after click the element.

- ``LOLLIPOPMouseClickCircleOpacity``
   default 1.0, "none" means no change, element change opacity after click the element

- ``LOLLIPOPMouseClickCircleStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after click the element.

- ``LOLLIPOPMouseClickCircleStrokeWidth``
   default 0, "none" means no change, element change stroke width after click the element.

- ``LOLLIPOPMouseClickTextFromData``
   default "fourth", first,second,third,fourth column data click to show 

- ``LOLLIPOPMouseClickTextOpacity``
   default 1.0, text opacity after click the element

- ``LOLLIPOPMouseClickTextColor``
   default "red", text color after click the element

- ``LOLLIPOPMouseClickTextSize``
   default 8, text size after click the element

- ``LOLLIPOPMouseClickTextPostionX``
   default 1.0, text x position after click the element

- ``LOLLIPOPMouseClickTextPostionY``
   default 10.0, text y position after click the element

- ``LOLLIPOPMouseClickTextDrag``
   default true, [true/false], open/not open text drag function

::::::::::::::::::::
Mouse down
::::::::::::::::::::

- ``LOLLIPOPMouseDownDisplay``
   default false, [true/false], open/not open mouse mouse down event of LOLLIPOP module

- ``LOLLIPOPMouseDownColor``
   default "green", "none" means no change, element change color after mouse down the element

- ``LOLLIPOPMouseDownCircleSize``
   default 4, "none" means no change, element change circle size after mouse down the element.

- ``LOLLIPOPMouseDownCircleOpacity``
   default 1.0, "none" means no change, element change opacity after mouse down the element

- ``LOLLIPOPMouseDownCircleStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse down the element.

- ``LOLLIPOPMouseDownCircleStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse down the element.

::::::::::::::::::::
Mouse enter
::::::::::::::::::::

- ``LOLLIPOPMouseEnterDisplay``
   default false, [true/false], open/not open mouse mouse enter event of LOLLIPOP module

- ``LOLLIPOPMouseEnterColor``
   default "yellow", "none" means no change, element change color after mouse enter the element

- ``LOLLIPOPMouseEnterCircleSize``
   default 4, "none" means no change, element change circle size after mouse enter the element.

- ``LOLLIPOPMouseEnterCircleOpacity``
   default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``LOLLIPOPMouseEnterCircleStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse enter the element.

- ``LOLLIPOPMouseEnterCircleStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse enter the element.

::::::::::::::::::::
Mouse leave
::::::::::::::::::::

- ``LOLLIPOPMouseLeaveDisplay``
   default false, [true/false], open/not open mouse mouse leave event of LOLLIPOP module

- ``LOLLIPOPMouseLeaveColor``
   default "pink", "none" means no change, element change color after mouse leave the element

- ``LOLLIPOPMouseLeaveCircleSize``
   default 4, "none" means no change, element change circle size after mouse leave the element.

- ``LOLLIPOPMouseLeaveCircleOpacity``
   default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``LOLLIPOPMouseLeaveCircleStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse leave the element.

- ``LOLLIPOPMouseLeaveCircleStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse leave the element.

::::::::::::::::::::
Mouse move
::::::::::::::::::::

- ``LOLLIPOPMouseMoveDisplay``
   default false, [true/false], open/not open mouse mouse move event of LOLLIPOP module

- ``LOLLIPOPMouseMoveColor``
   default "red", "none" means no change, element change color after mouse move the element

- ``LOLLIPOPMouseMoveCircleSize``
   default 2, "none" means no change, element change circle size after mouse move the element.

- ``LOLLIPOPMouseMoveCircleOpacity``
   default 1.0, "none" means no change, element change opacity after mouse move the element

- ``LOLLIPOPMouseMoveCircleStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse move the element.

- ``LOLLIPOPMouseMoveCircleStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse move the element.

::::::::::::::::::::
Mouse out
::::::::::::::::::::

- ``LOLLIPOPMouseOutDisplay``
   default false, [true/false], open/not open mouse mouse out event of LOLLIPOP module

- ``LOLLIPOPMouseOutAnimationTime``
   default 500, animation time after mouse out the element

- ``LOLLIPOPMouseOutColor``
   default "red", "none" means no change, element change color after mouse out the element

- ``LOLLIPOPMouseOutCircleSize``
   default 2, "none" means no change, element change circle size after mouse out the element.

- ``LOLLIPOPMouseOutCircleOpacity``
   default 1.0, "none" means no change, element change opacity after mouse out the element

- ``LOLLIPOPMouseOutCircleStrokeColor``
   default "red", "none" means no change, element change stroke color after mouse out the element.

- ``LOLLIPOPMouseOutCircleStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse out the element.

::::::::::::::::::::
Mouse up
::::::::::::::::::::

- ``LOLLIPOPMouseUpDisplay``
   default false, [true/false], open/not open mouse mouse up event of LOLLIPOP module

- ``LOLLIPOPMouseUpColor``
   default "grey", "none" means no change, element change color after mouse up the element

- ``LOLLIPOPMouseUpCircleSize``
   default 4, "none" means no change, element change circle size after mouse up the element.

- ``LOLLIPOPMouseUpCircleOpacity``
   default 1.0, "none" means no change, element change opacity after mouse up the element

- ``LOLLIPOPMouseUpCircleStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse up the element.

- ``LOLLIPOPMouseUpCircleStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse up the element.

::::::::::::::::::::
Mouse over
::::::::::::::::::::

- ``LOLLIPOPMouseOverDisplay``
   default false, [true/false], open/not open mouse mouse Over event of LOLLIPOP module

- ``LOLLIPOPMouseOverColor``
   default "red", "none" means no change, element change color after mouse Over the element

- ``LOLLIPOPMouseOverCircleSize``
   default 2, "none" means no change, element change circle size after mouse Over the element.

- ``LOLLIPOPMouseOverCircleOpacity``
   default 1.0, "none" means no change, element change opacity after mouse Over the element

- ``LOLLIPOPMouseOverCircleStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse Over the element.

- ``LOLLIPOPMouseOverCircleStrokeWidth``
   default 3, "none" means no change, element change stroke width after mouse Over the element.

```````````````````
GENE module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in GENE module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - GENE module
         GENEMouseEvent : true,
         GENEMouseClickDisplay : false,
         GENEMouseClickColor : "red",
         GENEMouseClickArcOpacity : 1.0,
         GENEMouseClickArcStrokeColor : "#F26223",
         GENEMouseClickArcStrokeWidth : 1,
         GENEMouseClickTextFromData : "fourth",
         GENEMouseClickTextOpacity : 1,
         GENEMouseClickTextColor : "red",
         GENEMouseClickTextSize : 8,
         GENEMouseClickTextPostionX : 0,
         GENEMouseClickTextPostionY : 0,
         GENEMouseClickTextDrag : true,
         GENEMouseDownDisplay : false,
         GENEMouseDownColor : "green",
         GENEMouseDownArcOpacity : 1.0,
         GENEMouseDownArcStrokeColor : "#F26223",
         GENEMouseDownArcStrokeWidth : 0,
         GENEMouseEnterDisplay : false,
         GENEMouseEnterColor : "yellow",
         GENEMouseEnterArcOpacity : 1.0,
         GENEMouseEnterArcStrokeColor : "#F26223",
         GENEMouseEnterArcStrokeWidth : 0,
         GENEMouseLeaveDisplay : false,
         GENEMouseLeaveColor : "pink",
         GENEMouseLeaveArcOpacity : 1.0,
         GENEMouseLeaveArcStrokeColor : "#F26223",
         GENEMouseLeaveArcStrokeWidth : 0,
         GENEMouseMoveDisplay : false,
         GENEMouseMoveColor : "red",
         GENEMouseMoveArcOpacity : 1.0,
         GENEMouseMoveArcStrokeColor : "#F26223",
         GENEMouseMoveArcStrokeWidth : 0,
         GENEMouseOutDisplay : false,
         GENEMouseOutAnimationTime : 500,
         GENEMouseOutColor : "red",
         GENEMouseOutArcOpacity : 1.0,
         GENEMouseOutArcStrokeColor : "red",
         GENEMouseOutArcStrokeWidth : 0,
         GENEMouseUpDisplay : false,
         GENEMouseUpColor : "grey",
         GENEMouseUpArcOpacity : 1.0,
         GENEMouseUpArcStrokeColor : "#F26223",
         GENEMouseUpArcStrokeWidth : 0,
         GENEMouseOverDisplay : false,
         GENEMouseOverColor : "red",
         GENEMouseOverArcOpacity : 1.0,
         GENEMouseOverArcStrokeColor : "#F26223",
         GENEMouseOverArcStrokeWidth : 3,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``GENEMouseEvent``
   default false, [true/false], open/not open mouse event of GENE module

::::::::::::::::::::
Mouse click
::::::::::::::::::::

- ``GENEMouseClickDisplay``
   default true, [true/false], open/not open mouse click event of GENE module

- ``GENEMouseClickColor``
   default "red", "none" means no change, element change color after click the element

- ``GENEMouseClickArcOpacity``
   default 1.0, "none" means no change, element change opacity after click the element

- ``GENEMouseClickArcStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after click the element.

- ``GENEMouseClickArcStrokeWidth``
   default 1, "none" means no change, element change stroke width after click the element.

- ``GENEMouseClickTextFromData``
   default "fourth", first,second,third,fourth column data click to show 

- ``GENEMouseClickTextOpacity``
   default 1.0, text opacity after click the element

- ``GENEMouseClickTextColor``
   default "red", text color after click the element

- ``GENEMouseClickTextSize``
   default 8, text size after click the element

- ``GENEMouseClickTextPostionX``
   default 0, text x position after click the element

- ``GENEMouseClickTextPostionY``
   default 0, text y position after click the element

- ``GENEMouseClickTextDrag``
   default true, [true/false], open/not open text drag function

::::::::::::::::::::
Mouse down
::::::::::::::::::::

- ``GENEMouseDownDisplay``
   default false, [true/false], open/not open mouse mouse down event of GENE module

- ``GENEMouseDownColor``
   default "green", "none" means no change, element change color after mouse down the element

- ``GENEMouseDownArcOpacity``
   default 1.0, "none" means no change, element change opacity after mouse down the element

- ``GENEMouseDownArcStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse down the element.

- ``GENEMouseDownArcStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse down the element.

::::::::::::::::::::
Mouse enter
::::::::::::::::::::

- ``GENEMouseEnterDisplay``
   default false, [true/false], open/not open mouse mouse enter event of GENE module

- ``GENEMouseEnterColor``
   default "yellow", "none" means no change, element change color after mouse enter the element

- ``GENEMouseEnterArcOpacity``
   default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``GENEMouseEnterArcStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse enter the element.

- ``GENEMouseEnterArcStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse enter the element.

::::::::::::::::::::
Mouse leave
::::::::::::::::::::

- ``GENEMouseLeaveDisplay``
   default false, [true/false], open/not open mouse mouse leave event of GENE module

- ``GENEMouseLeaveColor``
   default "pink", "none" means no change, element change color after mouse leave the element

- ``GENEMouseLeaveArcOpacity``
   default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``GENEMouseLeaveArcStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse leave the element.

- ``GENEMouseLeaveArcStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse leave the element.

::::::::::::::::::::
Mouse move
::::::::::::::::::::

- ``GENEMouseMoveDisplay``
   default false, [true/false], open/not open mouse mouse move event of GENE module

- ``GENEMouseMoveColor``
   default "red", "none" means no change, element change color after mouse move the element

- ``GENEMouseMoveArcOpacity``
   default 1.0, "none" means no change, element change opacity after mouse move the element

- ``GENEMouseMoveArcStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse move the element.

- ``GENEMouseMoveArcStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse move the element.

::::::::::::::::::::
Mouse out
::::::::::::::::::::

- ``GENEMouseOutDisplay``
   default false, [true/false], open/not open mouse mouse out event of GENE module

- ``GENEMouseOutAnimationTime``
   default 500, animation time after mouse out the element

- ``GENEMouseOutColor``
   default "red", "none" means no change, element change color after mouse out the element

- ``GENEMouseOutArcOpacity``
   default 1.0, "none" means no change, element change opacity after mouse out the element

- ``GENEMouseOutArcStrokeColor``
   default "red", "none" means no change, element change stroke color after mouse out the element.

- ``GENEMouseOutArcStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse out the element.

::::::::::::::::::::
Mouse up
::::::::::::::::::::

- ``GENEMouseUpDisplay``
   default false, [true/false], open/not open mouse mouse up event of GENE module

- ``GENEMouseUpColor``
   default "grey", "none" means no change, element change color after mouse up the element

- ``GENEMouseUpArcOpacity``
   default 1.0, "none" means no change, element change opacity after mouse up the element

- ``GENEMouseUpArcStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse up the element.

- ``GENEMouseUpArcStrokeWidth``
   default 0, "none" means no change, element change stroke width after mouse up the element.

::::::::::::::::::::
Mouse over
::::::::::::::::::::

- ``GENEMouseOverDisplay``
   default false, [true/false], open/not open mouse mouse Over event of GENE module

- ``GENEMouseOverColor``
   default "red", "none" means no change, element change color after mouse Over the element

- ``GENEMouseOverArcOpacity``
   default 1.0, "none" means no change, element change opacity after mouse Over the element

- ``GENEMouseOverArcStrokeColor``
   default "#F26223", "none" means no change, element change stroke color after mouse Over the element.

- ``GENEMouseOverArcStrokeWidth``
   default 3, "none" means no change, element change stroke width after mouse Over the element.

```````````````````
CHORD module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in CHORD module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - CHORD module
         CHORDMouseEvent : true,
         CHORDMouseFillColorExcluded:"#FFFFFF",
         CHORDMouseClickDisplay : false,
         CHORDMouseClickOpacity : 1.0,
         CHORDMouseClickStrokeColor : "green",
         CHORDMouseClickStrokeWidth : 4,
         CHORDMouseDownDisplay : false,
         CHORDMouseDownOpacity : 1.0,
         CHORDMouseDownStrokeColor : "#F26223",
         CHORDMouseDownStrokeWidth : 4,
         CHORDMouseEnterDisplay : false,
         CHORDMouseEnterOpacity : 1.0,
         CHORDMouseEnterStrokeColor : "#F26223",
         CHORDMouseEnterStrokeWidth : 4,
         CHORDMouseLeaveDisplay : false,
         CHORDMouseLeaveOpacity : 1.0,
         CHORDMouseLeaveStrokeColor : "#F26223",
         CHORDMouseLeaveStrokeWidth : 4,
         CHORDMouseMoveDisplay : false,
         CHORDMouseMoveOpacity : 1.0,
         CHORDMouseMoveStrokeColor : "#F26223",
         CHORDMouseMoveStrokeWidth : 4,
         CHORDMouseOutDisplay : false,
         CHORDMouseOutAnimationTime : 500,
         CHORDMouseOutOpacity : 1.0,
         CHORDMouseOutStrokeColor : "red",
         CHORDMouseOutStrokeWidth : 4,
         CHORDMouseUpDisplay : false,
         CHORDMouseUpOpacity : 1.0,
         CHORDMouseUpStrokeColor : "#F26223",
         CHORDMouseOverDisplay : false,
         CHORDMouseOverOpacity : 1.0,
         CHORDMouseOverStrokeColor : "#F26223",
         CHORDMouseOverStrokeWidth : 3,
         CHORDMouseUpStrokeWidth : 4,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``CHORDMouseEvent``
   default true, [true/false], open/not open mouse event of CHORD module
   
- ``CHORDMouseFillColorExcluded``
   default "#FFFFFF", if the fill color of this chord match this parameter, this chord will be excluded from the mouse event.

::::::::::::::::::::
Mouse click
::::::::::::::::::::

- ``CHORDMouseClickDisplay``
   default true, [true/false], open/not open mouse click event of CHORD module

- ``CHORDMouseClickOpacity``
   default 1.0, "none" means no change, element change opacity after click the element

- ``CHORDMouseClickStrokeColor``
   default "green", "none" means no change, element change color after click the element

- ``CHORDMouseClickStrokeWidth``
   default 4, "none" means no change, element change stroke width after click the element.

::::::::::::::::::::
Mouse down
::::::::::::::::::::

- ``CHORDMouseDownDisplay``
   default false, [true/false], open/not open mouse mouse down event of CHORD module

- ``CHORDMouseDownOpacity``
   default 1.0, "none" means no change, element change opacity after mouse down the element

- ``CHORDMouseDownStrokeColor``
   default "#F26223", "none" means no change, element change color after mouse down the element

- ``CHORDMouseDownStrokeWidth``
   default 4, "none" means no change, element change stroke width after mouse down the element.

::::::::::::::::::::
Mouse enter
::::::::::::::::::::

- ``CHORDMouseEnterDisplay``
   default false, [true/false], open/not open mouse mouse enter event of CHORD module

- ``CHORDMouseEnterOpacity``
   default 1.0, "none" means no change, element change opacity after mouse enter the element

- ``CHORDMouseEnterStrokeColor``
   default "#F26223", "none" means no change, element change color after mouse enter the element

- ``CHORDMouseEnterStrokeWidth``
   default 4, "none" means no change, element change stroke width after mouse enter the element.

::::::::::::::::::::
Mouse leave
::::::::::::::::::::

- ``CHORDMouseLeaveDisplay``
   default false, [true/false], open/not open mouse mouse leave event of CHORD module

- ``CHORDMouseLeaveOpacity``
   default 1.0, "none" means no change, element change opacity after mouse leave the element

- ``CHORDMouseLeaveStrokeColor``
   default "#F26223", "none" means no change, element change color after mouse leave the element

- ``CHORDMouseLeaveStrokeWidth``
   default 4, "none" means no change, element change stroke width after mouse leave the element.

::::::::::::::::::::
Mouse move
::::::::::::::::::::

- ``CHORDMouseMoveDisplay``
   default false, [true/false], open/not open mouse mouse move event of CHORD module

- ``CHORDMouseMoveOpacity``
   default 1.0, "none" means no change, element change opacity after mouse move the element

- ``CHORDMouseMoveStrokeColor``
   default "#F26223", "none" means no change, element change color after mouse move the element

- ``CHORDMouseMoveStrokeWidth``
   default 4, "none" means no change, element change stroke width after mouse move the element.

::::::::::::::::::::
Mouse out
::::::::::::::::::::

- ``CHORDMouseOutDisplay``
   default false, [true/false], open/not open mouse mouse out event of CHORD module

- ``CHORDMouseOutAnimationTime``
   default 500, animation time after mouse out the element

- ``CHORDMouseOutOpacity``
   default 1.0, "none" means no change, element change opacity after mouse out the element

- ``CHORDMouseOutStrokeColor``
   default "red", "none" means no change, element change color after mouse out the element

- ``CHORDMouseOutStrokeWidth``
   default 4, "none" means no change, element change stroke width after mouse out the element.

::::::::::::::::::::
Mouse up
::::::::::::::::::::

- ``CHORDMouseUpDisplay``
   default false, [true/false], open/not open mouse mouse up event of CHORD module

- ``CHORDMouseUpOpacity``
   default 1.0, "none" means no change, element change opacity after mouse up the element

- ``CHORDMouseUpStrokeColor``
   default "#F26223", "none" means no change, element change color after mouse up the element

- ``CHORDMouseUpStrokeWidth``
   default 4, "none" means no change, element change stroke width after mouse up the element.

::::::::::::::::::::
Mouse over
::::::::::::::::::::

- ``CHORDMouseOverDisplay``
   default true, [true/false], open/not open mouse mouse over event of CHORD module

- ``CHORDMouseOverOpacity``
   default 1.0, "none" means no change, element change opacity after mouse over the element

- ``CHORDMouseOverStrokeColor``
   default "#F26223", "none" means no change, element change color after mouse over the element

- ``CHORDMouseOverStrokeWidth``
   default 3, "none" means no change, element change stroke width after mouse over the element.

```````````````````
REDIRECT module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in REDIRECT module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - REDIRECT module
         SNPxlink: false,
         GENExlink: false,
         LOLLIPOPxlink: false,
         HISTOGRAMxlink: false,
         ARCxlink: false,
         CNVxlink: false,
         SCATTERxlink: false,
         BUBBLExlink:false,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``SNPxlink``
   default false, [true/false], add/not xlink for SNP module

- ``GENExlink``
   default false, [true/false], add/not xlink for GENE module
         
- ``LOLLIPOPxlink``
   default false, [true/false], add/not xlink for LOLLIPOP module
            
- ``HISTOGRAMxlink``
   default false, [true/false], add/not xlink for HISTOGRAM module
               
- ``ARCxlink``
   default false, [true/false], add/not xlink for ARC module
                  
- ``CNVxlink``
   default false, [true/false], add/not xlink for CNV module
                     
- ``SCATTERxlink``
   default false, [true/false], add/not xlink for SCATTER module

- ``BUBBLExlink``
   default false, [true/false], add/not xlink for BUBBLE module

```````````````````
COMPARE module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in COMPARE module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - COMPARE module
         compareEvent:false,
         compareEventGroupGapRate:0.1,
         compareEventGroupDistance:0,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``compareEvent``
   default false, [true/false], open/not COMPARE module

- ``compareEventGroupGapRate``
   default 0.1, control the two-side gap rate on each group of genome
         
- ``compareEventGroupDistance``
   default 0, distance between two groups of genome

```````````````````
COMBINATION module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in COMBINATION module of **Customize Events** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize events - COMBINATION module
         SNPMouseCombinationEvent :false,
         SNPMouseCombinationImageDisplay :false,
         SNPMouseCombinationImageTitle :"This is image",
         SNPMouseCombinationImageTitleSize :5,
         SNPMouseCombinationImageTitleWeight :"bold",
         SNPMouseCombinationImageTitleColor :"black",
         SNPMouseCombinationImagePositionX :0,
         SNPMouseCombinationImagePositionY :0,
         SNPMouseCombinationImageHeight :200,
         SNPMouseCombinationImageWidth :300,
         SNPMouseCombinationGraphDisplay :false,
         SNPMouseCombinationGraphTitle :"This is graph",
         SNPMouseCombinationGraphTitleSize :5,
         SNPMouseCombinationGraphTitleWeight :"bold",
         SNPMouseCombinationGraphTitleColor :"black",
         SNPMouseCombinationGraphType :"histogram",   //histogram, pie, line
         SNPMouseCombinationGraphPositionX :0,
         SNPMouseCombinationGraphPositionY :0,
         SNPMouseCombinationGraphHeight :200,
         SNPMouseCombinationGraphWidth :300,
         SNPMouseCombinationGraphHistogramBarColor :"blue",
         SNPMouseCombinationGraphHistogramPadding :30,
         SNPMouseCombinationGraphHistogramPositionCorrectX :0,
         SNPMouseCombinationGraphPieAutoColor :true,
         SNPMouseCombinationGraphPieColor :["black","blue","orange","red","green"],
         SNPMouseCombinationGraphPieSize :50,
         SNPMouseCombinationGraphPieStroke :true,
         SNPMouseCombinationGraphPieStrokeColor :"black",
         SNPMouseCombinationGraphPieStrokeWidth :1,
         SNPMouseCombinationGraphPieOpacity :1.0,
         SNPMouseCombinationGraphLineType :"linear",
         SNPMouseCombinationGraphLineColor :"black",
         SNPMouseCombinationGraphLineWidth :1,
         SNPMouseCombinationGraphLinePoint :false,
         SNPMouseCombinationGraphLinePointSize :5,
         SNPMouseCombinationGraphLinePointAutoColor :true,
         SNPMouseCombinationGraphLinePointColor :["black","blue","orange","red","green"],
         SNPMouseCombinationGraphLinePointStroke :true,
         SNPMouseCombinationGraphLinePointStrokeColor :"black",
         SNPMouseCombinationGraphLinePointStrokeWidth :1,
         SNPMouseCombinationGraphLinePointOpacity :1,
         SNPMouseCombinationGraphLinePositionCorrectX :0,
         SNPMouseCombinationTextDisplay :false,
         SNPMouseCombinationTextColor :"red",
         SNPMouseCombinationTextSize :3,
         SNPMouseCombinationTextWeight :"bold",
         SNPMouseCombinationTextPositionCorrectX :0,
         SNPMouseCombinationTextPositionCorrectY :0,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

- ``SNPMouseCombinationEvent``
   default false, [true/false], open/not COMBINATION module for SNP module

::::::::::::::::::::
Image
::::::::::::::::::::

- ``SNPMouseCombinationImageDisplay``
   default false, [true/false], open/not image display in COMBINATION module for SNP module

- ``SNPMouseCombinationImageTitle``
   default "This is image", title of the image

- ``SNPMouseCombinationImageTitleSize``
   default 5, size of the title

- ``SNPMouseCombinationImageTitleWeight``
   default "bold", weight of title

- ``SNPMouseCombinationImageTitleColor``
   default "black", color of title
         
- ``SNPMouseCombinationImagePositionX``
   default 0, the X axis position of image

- ``SNPMouseCombinationImagePositionY``
   default 0, the Y axis position of image

- ``SNPMouseCombinationImageHeight``
   default 200, the height of image
   
- ``SNPMouseCombinationImageWidth``
   default 300, the Width of image

::::::::::::::::::::
Image
::::::::::::::::::::
   
- ``SNPMouseCombinationGraphDisplay``
   default false, [true/false], open/not graph display in COMBINATION module for SNP module
   
- ``SNPMouseCombinationGraphTitle``
   default "This is graph", title of the graph
   
- ``SNPMouseCombinationGraphTitleSize``
   default 5, size of the title   

- ``SNPMouseCombinationGraphTitleWeight``
   default "bold", weight of title

- ``SNPMouseCombinationGraphTitleColor``
   default "black", color of title
   
- ``SNPMouseCombinationGraphType``
   default "histogram", [histogram/pie/line], type of graph

- ``SNPMouseCombinationGraphPositionX``
   default 0, the X axis position of graph

- ``SNPMouseCombinationGraphPositionY``
   default 0, the Y axis position of graph

- ``SNPMouseCombinationGraphHeight``
   default 200, the height of graph
   
- ``SNPMouseCombinationGraphWidth``
   default 300, the Width of graph
   
- ``SNPMouseCombinationGraphHistogramBarColor``
   default "blue", the bar color of histogram graph
      
- ``SNPMouseCombinationGraphHistogramPadding``
   default 30, the padding between bar of histogram graph
      
- ``SNPMouseCombinationGraphHistogramPositionCorrectX``
   default 0, the correction distance of X axis in histogram
         
- ``SNPMouseCombinationGraphPieAutoColor``
   default true, [true/false], whether use auto color for pie graph or not
         
- ``SNPMouseCombinationGraphPieColor``
   default ["black","blue","orange","red","green"], the color for pie graph if auto color is false
            
- ``SNPMouseCombinationGraphPieSize``
   default 50, the size of pie graph
   
- ``SNPMouseCombinationGraphPieStroke``
   default true, [true/false], whether each pie has a stroke or not
            
- ``SNPMouseCombinationGraphPieStrokeColor``
   default "black", the color of stroke in pie
      
- ``SNPMouseCombinationGraphPieStrokeWidth``
   default 1, the width of stroke in pie
            
- ``SNPMouseCombinationGraphPieOpacity``
   default 1.0, the opacity of pie
         
- ``SNPMouseCombinationGraphLineType``
   default "linear", the line type for line graph
            
- ``SNPMouseCombinationGraphLineColor``
   default "black", the color of line in line graph
            
- ``SNPMouseCombinationGraphLineWidth``
   default 1, the width of line in line graph      
                     
- ``SNPMouseCombinationGraphLinePoint``
   default false, [true/false], whether display the broken point in line graph

- ``SNPMouseCombinationGraphLinePointSize``
   default 5, the size of broken point      
                     
- ``SNPMouseCombinationGraphLinePointAutoColor``
   default true, [true/false], whether display the broken point in auto color
      
- ``SNPMouseCombinationGraphLinePointColor``
   default ["black","blue","orange","red","green"], the color for broken point if auto color is false     
                     
- ``SNPMouseCombinationGraphLinePointStroke``
   default true, [true/false], whether display the broken point stroke
         
- ``SNPMouseCombinationGraphLinePointStrokeColor``
   default "black", the stroke color for broken point     
                     
- ``SNPMouseCombinationGraphLinePointStrokeWidth``
   default 1, the stroke width for broken point
            
- ``SNPMouseCombinationGraphLinePointOpacity``
   default 1, the opacity for broken point     
                     
- ``SNPMouseCombinationGraphLinePositionCorrectX``
   default 0, the correction distance of X axis for line 

- ``SNPMouseCombinationTextDisplay``
   default false, [true/false], whether display the text
         
- ``SNPMouseCombinationTextColor``
   default "red", the color for text   
                     
- ``SNPMouseCombinationTextSize``
   default 3, the size of text
            
- ``SNPMouseCombinationTextWeight``
   default "bold", the weight of text     
                     
- ``SNPMouseCombinationGraphLinePositionCorrectX``
   default 0, the correction distance of X axis for text 

- ``SNPMouseCombinationGraphLinePositionCorrectY``
   default 0, the correction distance of Y axis for text

-----------------------
5.4 Customize Tooltips
-----------------------

Note that for the modules containing tooltips function, MouseoverTooltipsHtml and a parameter in data row called html are available when the MouseOverTooltipsSetting is set to "custom".

```````````````````
 SNP module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in SNP module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - SNP module
             SNPMouseOverTooltipsSetting :"style1",
             SNPMouseOverTooltipsHtml : " ",
             SNPMouseOverTooltipsPosition : "absolute",
             SNPMouseOverTooltipsBackgroundColor : "white",
             SNPMouseOverTooltipsBorderStyle : "solid",
             SNPMouseOverTooltipsBorderWidth : 0,
             SNPMouseOverTooltipsPadding : "3px",
             SNPMouseOverTooltipsBorderRadius : "3px",
             SNPMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
 Tooltips content
:::::::::::::::::::

- ``SNPMouseOverTooltipsSetting``
    default "style1"

- ``SNPMouseOverTooltipsHtml``
    default " "

**Example**: change the tooltips content of SNP module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          SNPMouseOverTooltipsSetting :"style1",

     - .. code-block:: javascript

          SNPMouseOverTooltipsSetting :"custom",
          {chr: "EGFR", pos: "813" , value: "21", des: "G,T,L/R",html:"Gene : EGFR <br>Position(AA) : 813 <br>Sample number : 21 <br>Mutation information : G,T,L/R"},
          {chr: "EGFR", pos: "805" , value: "21", des: "G,T,L/R",html:"Gene : EGFR <br>Position(AA) : 805 <br>Sample number : 21 <br>Mutation information : G,T,L/R"},
          {chr: "EGFR", pos: "858" , value: "21", des: "G,T,L/R",html:"Gene : EGFR <br>Position(AA) : 858 <br>Sample number : 21 <br>Mutation information : G,T,L/R"},
          {chr: "EGFR", pos: "598" , value: "17", des: "T,G,G/V",html:"Gene : EGFR <br>Position(AA) : 598 <br>Sample number : 17 <br>Mutation information : T,G,G/V"},
          {chr: "EGFR", pos: "553" , value: "17", des: "T,G,G/V",html:"Gene : EGFR <br>Position(AA) : 553 <br>Sample number : 17 <br>Mutation information : T,G,G/V"},
          {chr: "EGFR", pos: "545" , value: "17", des: "T,G,G/V",html:"Gene : EGFR <br>Position(AA) : 545 <br>Sample number : 17 <br>Mutation information : T,G,G/V"},
          {chr: "EGFR", pos: "598" , value: "17", des: "T,G,G/V",html:"Gene : EGFR <br>Position(AA) : 598 <br>Sample number : 17 <br>Mutation information : T,G,G/V"},
          {chr: "EGFR", pos: "289" , value: "16", des: "T,C,A/V",html:"Gene : EGFR <br>Position(AA) : 289 <br>Sample number : 16 <br>Mutation information : T,C,A/V"},
          {chr: "EGFR", pos: "236" , value: "16", des: "T,C,A/V",html:"Gene : EGFR <br>Position(AA) : 236 <br>Sample number : 16 <br>Mutation information : T,C,A/V"},
          {chr: "EGFR", pos: "289" , value: "16", des: "T,C,A/V",html:"Gene : EGFR <br>Position(AA) : 289 <br>Sample number : 16 <br>Mutation information : T,C,A/V"},
          {chr: "EGFR", pos: "244" , value: "16", des: "T,C,A/V",html:"Gene : EGFR <br>Position(AA) : 244 <br>Sample number : 16 <br>Mutation information : T,C,A/V"},
          {chr: "EGFR", pos: "692" , value: "7", des: "-,GGAATTAAGAGAAGC,KELREA/K",html:"Gene : EGFR <br>Position(AA) : 692 <br>Sample number : 7 <br>Mutation information : -,GGAATTAAGAGAAGC,KELREA/K"},
          {chr: "EGFR", pos: "745" , value: "7", des: "-,GGAATTAAGAGAAGC,KELREA/K",html:"Gene : EGFR <br>Position(AA) : 745 <br>Sample number : 7 <br>Mutation information : -,GGAATTAAGAGAAGC,KELREA/K"},
          {chr: "EGFR", pos: "700" , value: "7", des: "-,GGAATTAAGAGAAGC,KELREA/K",html:"Gene : EGFR <br>Position(AA) : 700 <br>Sample number : 7 <br>Mutation information : -,GGAATTAAGAGAAGC,KELREA/K"},
          {chr: "EGFR", pos: "244" , value: "6", des: "A,G,A/T",html:"Gene : EGFR <br>Position(AA) : 244 <br>Sample number : 6 <br>Mutation information : A,G,A/T"},
          {chr: "EGFR", pos: "289" , value: "6", des: "A,G,A/T",html:"Gene : EGFR <br>Position(AA) : 289 <br>Sample number : 6 <br>Mutation information : A,G,A/T"},

   * - Image change

     - .. image:: _images/API_main_customize_tooltips_SNP01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_tooltips_SNP01_before.html
     
     - .. image:: _images/API_main_customize_tooltips_SNP01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_tooltips_SNP01_after.html

:::::::::::::::::::
 Tooltips style
:::::::::::::::::::

- ``SNPMouseOverTooltipsPosition``
    default "absolute"

- ``SNPMouseOverTooltipsBackgroundColor``
    default "white"

- ``SNPMouseOverTooltipsBorderStyle``
    default "solid"

- ``SNPMouseOverTooltipsBorderWidth``
    default 0

- ``SNPMouseOverTooltipsPadding``
    default "3px"

- ``SNPMouseOverTooltipsBorderRadius``
    default "3px"

- ``SNPMouseOverTooltipsOpacity``
    default 0.8

**Example**: change the tooltips style of SNP module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          SNPMouseOverTooltipsBorderWidth : 0,
          SNPMouseOverTooltipsPadding : "3px",
          SNPMouseOverTooltipsBorderRadius : "3px",
          SNPMouseOverTooltipsOpacity : 1,

     - .. code-block:: javascript

          SNPMouseOverTooltipsBorderWidth : 1,
          SNPMouseOverTooltipsPadding : "5px",
          SNPMouseOverTooltipsBorderRadius : "10px",
          SNPMouseOverTooltipsOpacity : 0.8,

   * - Image change

     - .. image:: _images/API_main_customize_tooltips_SNP02_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_tooltips_SNP02_before.html
     
     - .. image:: _images/API_main_customize_tooltips_SNP02_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_tooltips_SNP02_after.html

```````````````````
 SCATTER module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in SCATTER module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - SCATTER module
             SCATTERMouseOverTooltipsSetting :"style1",
             SCATTERMouseOverTooltipsHtml : " ",
             SCATTERMouseOverTooltipsPosition : "absolute",
             SCATTERMouseOverTooltipsBackgroundColor : "white",
             SCATTERMouseOverTooltipsBorderStyle : "solid",
             SCATTERMouseOverTooltipsBorderWidth : 0,
             SCATTERMouseOverTooltipsPadding : "3px",
             SCATTERMouseOverTooltipsBorderRadius : "3px",
             SCATTERMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
 Tooltips content
:::::::::::::::::::

- ``SCATTERMouseOverTooltipsSetting``
    default "style1"

- ``SCATTERMouseOverTooltipsHtml``
    default " "

**Example**: change the tooltips content of SCATTER module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          SCATTERMouseOverTooltipsSetting :"style1",
          SCATTERMouseOverTooltipsHtml : " ",

     - .. code-block:: javascript

          SCATTERMouseOverTooltipsSetting :"custom",
          {chr: "1", start: "1102484", end: "1102578", name: "hsa-mir-200b", des: "breast cancer",html:"chr : 1 <br>start : 1102484 <br>end : 1102578 <br>name : hsa-mir-200b <br>cancer type : breast cancer"},
          {chr: "11", start: "122017230", end: "122017301", name: "hsa-let-7a-2", des: "ovarian cancer",html:"chr : 11 <br>start : 122017230 <br>end : 122017301 <br>name : hsa-let-7a-2 <br>cancer type : ovarian cancer"},
          {chr: "22", start: "46508629", end: "46508702", name: "hsa-let-7a-3", des: "leukemia cancer",html:"chr : 22 <br>start : 46508629 <br>end : 46508702 <br>name : hsa-let-7a-3 <br>cancer type : leukemia cancer"},
          {chr: "14", start: "101349316", end: "101349412", name: "hsa-mir-127", des: "breast cancer",html:"chr : 14 <br>start : 101349316 <br>end : 101349412 <br>name : hsa-mir-127 <br>cancer type : breast cancer"},

   * - Image change

     - .. image:: _images/API_main_customize_tooltips_SCATTER01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_tooltips_SCATTER01_before.html
     
     - .. image:: _images/API_main_customize_tooltips_SCATTER01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_tooltips_SCATTER01_after.html

:::::::::::::::::::
 Tooltips style
:::::::::::::::::::

- ``SCATTERMouseOverTooltipsPosition``
    default "absolute"

- ``SCATTERMouseOverTooltipsBackgroundColor``
    default "white"

- ``SCATTERMouseOverTooltipsBorderStyle``
    default "solid"

- ``SCATTERMouseOverTooltipsBorderWidth``
    default 0

- ``SCATTERMouseOverTooltipsPadding``
    default "3px"

- ``SCATTERMouseOverTooltipsBorderRadius``
    default "3px"

- ``SCATTERMouseOverTooltipsOpacity``
    default 0.8

**Example**: change the tooltips style of SCATTER module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          SCATTERMouseOverTooltipsBackgroundColor : "white",
          SCATTERMouseOverTooltipsBorderWidth : 0,
          SCATTERMouseOverTooltipsBorderRadius : "3px",
          SCATTERMouseOverTooltipsOpacity : 0.8,

     - .. code-block:: javascript

          SCATTERMouseOverTooltipsBackgroundColor : "#DCDCDC",
          SCATTERMouseOverTooltipsBorderWidth : 1,
          SCATTERMouseOverTooltipsBorderRadius : "5px",
          SCATTERMouseOverTooltipsOpacity : 0.7,

   * - Image change

     - .. image:: _images/API_main_customize_tooltips_SCATTER02_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_tooltips_SCATTER02_before.html
     
     - .. image:: _images/API_main_customize_tooltips_SCATTER02_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_main_customize_tooltips_SCATTER02_after.html

```````````````````
 LINK module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in LINK module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - LINK module
             LINKMouseOverTooltipsSetting : "style1",  //custom, style1
             LINKMouseOverTooltipsHtml : " ",
             LINKMouseOverTooltipsPosition : "absolute",
             LINKMouseOverTooltipsBackgroundColor : "white",
             LINKMouseOverTooltipsBorderStyle : "solid",
             LINKMouseOverTooltipsBorderWidth : 0,
             LINKMouseOverTooltipsPadding : "3px",
             LINKMouseOverTooltipsBorderRadius : "3px",
             LINKMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
 Tooltips content
:::::::::::::::::::

- ``LINKMouseOverTooltipsSetting``
    default "style1"

- ``LINKMouseOverTooltipsHtml``
    default " "

:::::::::::::::::::
 Tooltips style
:::::::::::::::::::

- ``LINKMouseOverTooltipsPosition``
    default "absolute"

- ``LINKMouseOverTooltipsBackgroundColor``
    default "white"

- ``LINKMouseOverTooltipsBorderStyle``
    default "solid"

- ``LINKMouseOverTooltipsBorderWidth``
    default 0

- ``LINKMouseOverTooltipsPadding``
    default "3px"

- ``LINKMouseOverTooltipsBorderRadius``
    default "3px"

- ``LINKMouseOverTooltipsOpacity``
    default 0.8

```````````````````
 CNV module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in CNV module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - CNV module
             CNVMouseOverTooltipsSetting :"style1",
             CNVMouseOverTooltipsHtml : " ",
             CNVMouseOverTooltipsPosition : "absolute",
             CNVMouseOverTooltipsBackgroundColor : "white",
             CNVMouseOverTooltipsBorderStyle : "solid",
             CNVMouseOverTooltipsBorderWidth : 0,
             CNVMouseOverTooltipsPadding : "3px",
             CNVMouseOverTooltipsBorderRadius : "3px",
             CNVMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
 Tooltips content
:::::::::::::::::::

- ``CNVMouseOverTooltipsSetting``
    default "style1"

- ``CNVMouseOverTooltipsHtml``
    default " "

:::::::::::::::::::
 Tooltips style
:::::::::::::::::::

- ``CNVMouseOverTooltipsPosition``
    default "absolute"

- ``CNVMouseOverTooltipsBackgroundColor``
    default "white"

- ``CNVMouseOverTooltipsBorderStyle``
    default "solid"

- ``CNVMouseOverTooltipsBorderWidth``
    default 0

- ``CNVMouseOverTooltipsPadding``
    default "3px"

- ``CNVMouseOverTooltipsBorderRadius``
    default "3px"

- ``CNVMouseOverTooltipsOpacity``
    default 0.8

```````````````````
 ARC module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in ARC module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - ARC module
             ARCMouseOverTooltipsSetting :"style1",
             ARCMouseOverTooltipsHtml : " ",
             ARCMouseOverTooltipsPosition : "absolute",
             ARCMouseOverTooltipsBackgroundColor : "white",
             ARCMouseOverTooltipsBorderStyle : "solid",
             ARCMouseOverTooltipsBorderWidth : 0,
             ARCMouseOverTooltipsPadding : "3px",
             ARCMouseOverTooltipsBorderRadius : "3px",
             ARCMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
 Tooltips content
:::::::::::::::::::

- ``ARCMouseOverTooltipsSetting``
    default "style1 "

- ``ARCMouseOverTooltipsHtml``
    default " "

:::::::::::::::::::
 Tooltips style
:::::::::::::::::::

- ``ARCMouseOverTooltipsPosition``
    default "absolute"

- ``ARCMouseOverTooltipsBackgroundColor``
    default "white"

- ``ARCMouseOverTooltipsBorderStyle``
    default "solid"

- ``ARCMouseOverTooltipsBorderWidth``
    default 0

- ``ARCMouseOverTooltipsPadding``
    default "3px"

- ``ARCMouseOverTooltipsBorderRadius``
    default "3px"

- ``ARCMouseOverTooltipsOpacity``
    default 0.8

```````````````````
 HEATMAP module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in HEATMAP module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - HEATMAP module
             HEATMAPMouseOverTooltipsSetting :"style1",
             HEATMAPMouseOverTooltipsHtml : " ",
             HEATMAPMouseOverTooltipsPosition : "absolute",
             HEATMAPMouseOverTooltipsBackgroundColor : "white",
             HEATMAPMouseOverTooltipsBorderStyle : "solid",
             HEATMAPMouseOverTooltipsBorderWidth : 0,
             HEATMAPMouseOverTooltipsPadding : "3px",
             HEATMAPMouseOverTooltipsBorderRadius : "3px",
             HEATMAPMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
 Tooltips content
:::::::::::::::::::

- ``HEATMAPMouseOverTooltipsSetting``
    default "style1"

- ``HEATMAPMouseOverTooltipsHtml``
    default " "

:::::::::::::::::::
 Tooltips style
:::::::::::::::::::

- ``HEATMAPMouseOverTooltipsPosition``
    default "absolute"

- ``HEATMAPMouseOverTooltipsBackgroundColor``
    default "white"

- ``HEATMAPMouseOverTooltipsBorderStyle``
    default "solid"

- ``HEATMAPMouseOverTooltipsBorderWidth``
    default 0

- ``HEATMAPMouseOverTooltipsPadding``
    default "3px"

- ``HEATMAPMouseOverTooltipsBorderRadius``
    default "3px"

- ``HEATMAPMouseOverTooltipsOpacity``
    default 0.8

```````````````````
BUBBLE module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in BUBBLE module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - BUBBLE module
         BUBBLEMouseOverTooltipsSetting : "style1",
         BUBBLEMouseOverTooltipsHtml : " ",
         BUBBLEMouseOverTooltipsPosition : "absolute",
         BUBBLEMouseOverTooltipsBackgroundColor : "white",
         BUBBLEMouseOverTooltipsBorderStyle : "solid",
         BUBBLEMouseOverTooltipsBorderWidth : 0,
         BUBBLEMouseOverTooltipsPadding : "3px",
         BUBBLEMouseOverTooltipsBorderRadius : "3px",
         BUBBLEMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
Tooltips content
:::::::::::::::::::

- ``BUBBLEMouseOverTooltipsSetting``
   default "style1"

- ``BUBBLEMouseOverTooltipsHtml``
   default " "

:::::::::::::::::::
Tooltips style
:::::::::::::::::::

- ``BUBBLEMouseOverTooltipsPosition``
   default "absolute"

- ``BUBBLEMouseOverTooltipsBackgroundColor``
   default "white"

- ``BUBBLEMouseOverTooltipsBorderStyle``
   default "solid"

- ``BUBBLEMouseOverTooltipsBorderWidth``
   default 0

- ``BUBBLEMouseOverTooltipsPadding``
   default "3px"

- ``BUBBLEMouseOverTooltipsBorderRadius``
   default "3px"

- ``BUBBLEMouseOverTooltipsOpacity``
   default 0.8

```````````````````
 HISTOGRAM module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in HISTOGRAM module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - HISTOGRAM module
             HISTOGRAMMouseOverTooltipsSetting : "style1",
             HISTOGRAMMouseOverTooltipsHtml : " ",
             HISTOGRAMMouseOverTooltipsPosition : "absolute",
             HISTOGRAMMouseOverTooltipsBackgroundColor : "white",
             HISTOGRAMMouseOverTooltipsBorderStyle : "solid",
             HISTOGRAMMouseOverTooltipsBorderWidth : 0,
             HISTOGRAMMouseOverTooltipsPadding : "3px",
             HISTOGRAMMouseOverTooltipsBorderRadius : "3px",
             HISTOGRAMMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
 Tooltips content
:::::::::::::::::::

- ``HISTOGRAMMouseOverTooltipsSetting``
    default "style1"

- ``HISTOGRAMMouseOverTooltipsHtml``
    default " "

:::::::::::::::::::
 Tooltips style
:::::::::::::::::::

- ``HISTOGRAMMouseOverTooltipsPosition``
    default "absolute"

- ``HISTOGRAMMouseOverTooltipsBackgroundColor``
    default "white"

- ``HISTOGRAMMouseOverTooltipsBorderStyle``
    default "solid"

- ``HISTOGRAMMouseOverTooltipsBorderWidth``
    default 0

- ``HISTOGRAMMouseOverTooltipsPadding``
    default "3px"

- ``HISTOGRAMMouseOverTooltipsBorderRadius``
    default "3px"

- ``HISTOGRAMMouseOverTooltipsOpacity``
    default 0.8

```````````````````
 LINE module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in LINE module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - LINE module
             LINEMouseOverTooltipsHtml : " ",
             LINEMouseOverTooltipsPosition : "absolute",
             LINEMouseOverTooltipsBackgroundColor : "white",
             LINEMouseOverTooltipsBorderStyle : "solid",
             LINEMouseOverTooltipsBorderWidth : 0,
             LINEMouseOverTooltipsPadding : "3px",
             LINEMouseOverTooltipsBorderRadius : "3px",
             LINEMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
 Tooltips content
:::::::::::::::::::

- ``LINEMouseOverTooltipsHtml``
    default " "

:::::::::::::::::::
 Tooltips style
:::::::::::::::::::

- ``LINEMouseOverTooltipsPosition``
    default "absolute"

- ``LINEMouseOverTooltipsBackgroundColor``
    default "white"

- ``LINEMouseOverTooltipsBorderStyle``
    default "solid"

- ``LINEMouseOverTooltipsBorderWidth``
    default 0

- ``LINEMouseOverTooltipsPadding``
    default "3px"

- ``LINEMouseOverTooltipsBorderRadius``
    default "3px"

- ``LINEMouseOverTooltipsOpacity``
    default 0.8
   
```````````````````
WIG module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in WIG module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - WIG module
         WIGMouseOverTooltipsHtml : " ",
         WIGMouseOverTooltipsPosition : "absolute",
         WIGMouseOverTooltipsBackgroundColor : "white",
         WIGMouseOverTooltipsBorderStyle : "solid",
         WIGMouseOverTooltipsBorderWidth : 0,
         WIGMouseOverTooltipsPadding : "3px",
         WIGMouseOverTooltipsBorderRadius : "3px",
         WIGMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
Tooltips content
:::::::::::::::::::

- ``WIGMouseOverTooltipsHtml``
   default " "

:::::::::::::::::::
Tooltips style
:::::::::::::::::::

- ``WIGMouseOverTooltipsPosition``
   default "absolute"

- ``WIGMouseOverTooltipsBackgroundColor``
   default "white"

- ``WIGMouseOverTooltipsBorderStyle``
   default "solid"

- ``WIGMouseOverTooltipsBorderWidth``
   default 0

- ``WIGMouseOverTooltipsPadding``
   default "3px"

- ``WIGMouseOverTooltipsBorderRadius``
   default "3px"

- ``WIGMouseOverTooltipsOpacity``
   default 0.8
   
```````````````````
LOLLIPOP module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in LOLLIPOP module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - LOLLIPOP module
         LOLLIPOPMouseOverTooltipsSetting : "style1",
         LOLLIPOPMouseOverTooltipsHtml : " ",
         LOLLIPOPMouseOverTooltipsPosition : "absolute",
         LOLLIPOPMouseOverTooltipsBackgroundColor : "white",
         LOLLIPOPMouseOverTooltipsBorderStyle : "solid",
         LOLLIPOPMouseOverTooltipsBorderWidth : 0,
         LOLLIPOPMouseOverTooltipsPadding : "3px",
         LOLLIPOPMouseOverTooltipsBorderRadius : "3px",
         LOLLIPOPMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
Tooltips content
:::::::::::::::::::

- ``LOLLIPOPMouseOverTooltipsSetting``
   default "style1"

- ``LOLLIPOPMouseOverTooltipsHtml``
   default " "

:::::::::::::::::::
Tooltips style
:::::::::::::::::::

- ``LOLLIPOPMouseOverTooltipsPosition``
   default "absolute"

- ``LOLLIPOPMouseOverTooltipsBackgroundColor``
   default "white"

- ``LOLLIPOPMouseOverTooltipsBorderStyle``
   default "solid"

- ``LOLLIPOPMouseOverTooltipsBorderWidth``
   default 0

- ``LOLLIPOPMouseOverTooltipsPadding``
   default "3px"

- ``LOLLIPOPMouseOverTooltipsBorderRadius``
   default "3px"

- ``LOLLIPOPMouseOverTooltipsOpacity``
   default 0.8

```````````````````
GENE module
```````````````````

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(1)All configuration parameters
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Here we show all the configuration parameters in GENE module of **Customize Tooltips** class.

.. code-block:: javascript

	  NGCircos01 = new NGCircos(NGCircosGenome,{
	     // Main configuration - Customize Tooltips - GENE module
         GENEMouseOverTooltipsSetting : "style1",
         GENEMouseOverTooltipsHtml : " ",
         GENEMouseOverTooltipsPosition : "absolute",
         GENEMouseOverTooltipsBackgroundColor : "white",
         GENEMouseOverTooltipsBorderStyle : "solid",
         GENEMouseOverTooltipsBorderWidth : 0,
         GENEMouseOverTooltipsPadding : "3px",
         GENEMouseOverTooltipsBorderRadius : "3px",
         GENEMouseOverTooltipsOpacity : 0.8,
	  });

::::::::::::::::::::::::::::::
(2)Configuration and examples
::::::::::::::::::::::::::::::

:::::::::::::::::::
Tooltips content
:::::::::::::::::::

- ``GENEMouseOverTooltipsSetting``
   default "style1"

- ``GENEMouseOverTooltipsHtml``
   default " "

:::::::::::::::::::
Tooltips style
:::::::::::::::::::

- ``GENEMouseOverTooltipsPosition``
   default "absolute"

- ``GENEMouseOverTooltipsBackgroundColor``
   default "white"

- ``GENEMouseOverTooltipsBorderStyle``
   default "solid"

- ``GENEMouseOverTooltipsBorderWidth``
   default 0

- ``GENEMouseOverTooltipsPadding``
   default "3px"

- ``GENEMouseOverTooltipsBorderRadius``
   default "3px"

- ``GENEMouseOverTooltipsOpacity``
   default 0.8

```````````````````
 Advanced tooltips
```````````````````
Tooltips is a html element : ``<div class="NGCircos(Module)Tooltip">``. So web developers can use CSS to configure tooltips.

::::::::::::::::::::::::::::::
(1)CSS API for advanced users
::::::::::::::::::::::::::::::

.. code-block:: html

	<style>
	   .NGCircosMODULETooltip {   //eg: NGCircosSNPTooltip
   	    background-color: #000;
   	    color: white;
   	    font-size: 18px;
   	    font-weight: bold;
   	    font-family: Arial;
          ......
	   }
	</style>

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
(2)Example: CSS API for SNP module
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After
   
   * - Code change
   
     - .. code-block:: html

	  <style>
	  .NGCircosSNPTooltip {
	      border-color: #000;
	      color: white;
	      font-size: 18px;
	      font-weight: 100;
	      font-family: Arial;
	  }
	  </style>

     - .. code-block:: html

	  <style>
	  .NGCircosSNPTooltip {
	      border-color: #000;
	      color: red;
	      font-size: 18px;
	      font-weight: bold;
	      font-family: Arial;
	  }
	  </style>

   * - Image change
   
     - .. image:: _images/API_CSS_tooltips_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_CSS_tooltips_before.html
     
     - .. image:: _images/API_CSS_tooltips_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_CSS_tooltips_after.html

===========================
6. API: Data configuration
===========================

-------------------
6.1 SNP module
-------------------

.. code-block:: javascript

	var SNP01 = [ "SNP01" , {
	  maxRadius: 205,
	  minRadius: 153,
     SNPFillColorType:"specific"
	  SNPFillColor: "#9400D3",
     SNPFillr2Color:["#ff0031","#ff0031","#ff0031","#ff0031","#ff0031"],
     ValueAxisManualScale:false,
     ValueAxisMaxScale:10,
     ValueAxisMinScale:0,
	  PointType: "circle",
	  circleSize: 2,
	  rectWidth: 2,
	  rectHeight: 2,
     SNPAnimationDisplay: false,
     SNPAnimationInitialPositionX:0,
     SNPAnimationInitialPositionY:0,
     SNPAnimationTime: 2000,
     SNPAnimationDelay: 20,
     SNPAnimationType: "bounce",  //linear,circle,elastic,bounce
	} , [
	  {chr: "10", pos: "100315722", value: "20.2218", des: "rs603424", color: "rgb(153,102,0)",r2value:"0",html:" "},
	  {chr: "10", pos: "101219450", value: "19", des: "rs11190870", color: "rgb(153,102,0)",r2value:"0"},
	  {chr: "10", pos: "103086421", value: "25.1549", des: "rs11191548", color: "rgb(153,102,0)",r2value:"0"},
	  {chr: "10", pos: "112998590", value: "74.0969", des: "rs7903146", color: "rgb(153,102,0)",r2value:"0"},
	  {chr: "10", pos: "121577821", value: "169.699", des: "rs2981579", color: "rgb(153,102,0)",r2value:"0"},
	   ......
	  {chr: "X", pos: "5266661", value: "24.699", des: "rs6638512", color: "rgb(153,153,153)",r2value:"0"},
	  {chr: "X", pos: "67343176", value: "90.699", des: "rs2497938", color: "rgb(153,153,153)",r2value:"0"},
	  {chr: "X", pos: "69578860", value: "18.1549", des: "rs11796357", color: "rgb(153,153,153)",r2value:"0"},
	  {chr: "X", pos: "79241621", value: "32.699", des: "rs5912838", color: "rgb(153,153,153)",r2value:"0"},
	]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``maxRadius``
    default 205, max radius to show SNPs with max vlaue

- ``minRadius``
    default 173, min radius to show SNPs with min vlaue

- ``SNPFillColorType``
    default "specific", [specific/r2], whether specify a color to SNP or assign a color based on r2 value and r2 color list.
   
- ``SNPFillColor``
    default "#9400D3", SNP color
   
- ``SNPFille2Color``
    default ["#ff0031","#ff0031","#ff0031","#ff0031","#ff0031"], r2 color list from high to low, r2 value between 1 to 0 are assigned to relative color, 1-0.8 to first, 0.8-0.6 to second, and so on.

- ``ValueAxisManualScale``
    default "false", [false/true], whether manually control the scale of value

- ``ValueAxisMaxScale``
    default "10", the maxmium value manually set for value
   
- ``ValueAxisMaxScale``
    default "0", the minimum value manually set for value

- ``PointType``
    default "circle", [circle/rect], circle/rect point

- ``circleSize``
    default 2, size of circle

- ``rectWidth``
    default 2, width of rect

- ``rectHeight``
    default 2, height of rect

**Example**: change data configuration of SNP module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After
   
   * - Code change
    
     - .. code-block:: javascript

          minRadius: 153,
          circleSize: 2,

     - .. code-block:: javascript

          minRadius: 103,
          circleSize: 3,

   * - Image change
    
     - .. image:: _images/API_data_configuration_SNP01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_SNP01_before.html
     
     - .. image:: _images/API_data_configuration_SNP01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_SNP01_after.html

- ``SNPAnimationDisplay``
    default "false", [true/false], open/not open animation event of SNP module

- ``SNPAnimationInitialPositionX``
    default 0, initial X axis position for SNP.

- ``SNPAnimationInitialPositionY``
    default 0, initial Y axis position for SNP.

- ``SNPAnimationTime``
    default 2000, specifies the animation time in milliseconds.

- ``SNPAnimationDelay``
    default 20, specifies the animation delay in milliseconds. 

- ``SNPAnimationType``
    default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

**Example**: SNP Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change
    
     - .. code-block:: javascript

          SNPFillColor: "#9400D3",
          SNPAnimationDisplay: true,
          SNPAnimationTime: 1000,
          SNPAnimationDelay: 0,
          SNPAnimationType: "circle",

     - .. code-block:: javascript

          SNPFillColor: "red",
          SNPAnimationDisplay: true,
          SNPAnimationTime: 2000,
          SNPAnimationDelay: 20,
          SNPAnimationType: "bounce",

   * - Image change
    
     - .. image:: _images/SNPAnimation01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/SNPAnimation01_before.html
     
     - .. image:: _images/SNPAnimation01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/SNPAnimation01_after.html

``````````````
Part 2 : Data
``````````````

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``pos``) is the position of the SNP.
- The 3 column(``value``) is the value(density, P-value, etc.) of the SNP.
- The 4 column(``des``) is the description of the SNP.
- The 5 column(``color``) is the color of this SNP point.
- The 6 column(``r2value``) is the r2 value for this SNP point especially prepared for locuszoom plot.
- The 7 column(``html``) is the html for tooltips.

-------------------
6.2 SCATTER module
-------------------

.. code-block:: javascript

	var SCATTER01 = [ "SCATTER01" , {
	  SCATTERRadius: 220,
	  innerCircleSize: 1,
	  outerCircleSize: 7,
	  innerCircleColor: "red",
	  outerCircleColor: "#CC3399",
	  innerPointType: "circle", //circle,rect
	  outerPointType: "circle", //circle,rect
	  innerrectWidth: 2,
	  innerrectHeight: 2,
	  outerrectWidth: 10,
	  outerrectHeight: 10,
	  outerCircleOpacity: 1,
	  random_data: 0,
      SCATTERAnimationDisplay: false,
      SCATTERAnimationTime: 2000,
      SCATTERAnimationDelay: 20,
      SCATTERAnimationType: "bounce",  //linear,circle,elastic,bounce
	} , [
	  {chr: "1", start: "1102484", end: "1102578", name: "hsa-mir-200b", des: "breast cancer",html:" "},
	  {chr: "11", start: "122017230", end: "122017301", name: "hsa-let-7a-2", des: "ovarian cancer"},
	  {chr: "22", start: "46508629", end: "46508702", name: "hsa-let-7a-3", des: "leukemia cancer"},
	  {chr: "14", start: "101349316", end: "101349412", name: "hsa-mir-127", des: "breast cancer"},
	]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``SCATTERRadius``
    default 220, radius of scatter circle

- ``innerCircleSize``
    default 1, inner circle size

- ``outerCircleSize``
    default 7, outer circle size

- ``innerCircleColor``
    default "red", inner circle color

- ``outerCircleColor``
    default "#CC3399", outer circle color

- ``innerPointType``
    default "circle", [circle/rect], circle/rect point

- ``outerPointType``
    default "circle", [circle/rect], circle/rect point

- ``innerrectWidth``
    default 2, width of inner rect

- ``innerrectHeight``
    default 2, height of inner rect

- ``outerrectWidth``
    default 2, width of outer rect

- ``outerrectHeight``
    default 2, height of outer rect

- ``outerCircleOpacity``
    default 1, opacity of outer circle

- ``random_data``
    default 0, scatter position fluctuation

**Example**: change data configuration of SCATTER module

.. list-table::

   :widths: 10 60 60
   :header-rows: 1

   * - Example
     
     - Before
     - After
   
   * - Code change

        - .. code-block:: javascript

          SCATTERRadius: 220,
          innerCircleSize: 1,
          outerCircleSize: 7,
          outerCircleColor: "#CC3399",
          outerCircleOpacity: 1,

     - .. code-block:: javascript

          SCATTERRadius: 190,
          innerCircleSize: 2,
          outerCircleSize: 9,
          outerCircleColor: "green",
          outerCircleOpacity: 0.5,

   * - Image change

     - .. image:: _images/API_data_configuration_SCATTER01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_SCATTER01_before.html

     - .. image:: _images/API_data_configuration_SCATTER01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_SCATTER01_after.html

- ``SCATTERAnimationDisplay``
    default "false", [true/false], open/not open animation event of SCATTER module

- ``SCATTERAnimationTime``
    default 2000, specifies the animation time in milliseconds.

- ``SCATTERAnimationDelay``
    default 20, specifies the animation delay in milliseconds. 

- ``SCATTERAnimationType``
    default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

**Example**: SCATTER Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example
     - Before
     - After
   
   * - Code change
     
     - .. code-block:: javascript

          outerCircleColor: "#CC3399",
          SCATTERAnimationDisplay: true,
          SCATTERAnimationTime: 2000,
          SCATTERAnimationDelay: 20,
          SCATTERAnimationType: "bounce",

     - .. code-block:: javascript

          outerCircleColor: "green",
          SCATTERAnimationDisplay: true,
          SCATTERAnimationTime: 1000,
          SCATTERAnimationDelay: 400,
          SCATTERAnimationType: "circle",

   * - Image change
    
     - .. image:: _images/SCATTERAnimation01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/SCATTERAnimation01_before.html

     - .. image:: _images/SCATTERAnimation01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/SCATTERAnimation01_after.html

``````````````
Part 2 : Data
``````````````

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``start``) is the start position of the scatter.
- The 3 column(``end``) is the end position of the scatter.
- The 4 column(``name``) is the name of the scatter.
- The 5 column(``des``) is the description of the scatter.
- The 6 column(``html``) is the html for tooltips.

-------------------
6.3 LINK module
-------------------

.. code-block:: javascript

	var LINK01 = [ "LINK01" , {
	  LinkRadius: 140,
	  LinkFillColor: "#F26223",
	  LinkWidth: 3,
     LinkType:"Q",
	  displayLinkAxis: true,
	  LinkAxisColor: "#B8B8B8",
	  LinkAxisWidth: 0.5,
	  LinkAxisPad: 3,
	  displayLinkLabel: true,
	  LinkLabelColor: "red",
	  LinkLabelSize: 13,
	  LinkLabelPad: 8,
     LINKAnimationDisplay: false,
     LINKAnimationDirection:"1to2", //1to2,2to1  [side1 to side2/side2 to side1]
     LINKAnimationTime: 2000,
     LINKAnimationDelay: 20,
     LINKAnimationType: "bounce",
	} , [
	  {fusion: "FGFR3--TACC3", g1chr: "4", g1start: "1795662", g1end: "1808986", g1name: "FGFR3", g2chr: "4", g2start: "1723217", g2end: "1746905", g2name: "TACC3",html:" "},
	  {fusion: "CCDC6--RET", g1chr: "10", g1start: "43595894", g1end: "43623714", g1name: "RET", g2chr: "10", g2start: "61552678", g2end: "61666182", g2name: "TACC3"},
	  {fusion: "ETV6--NTRK3", g1chr: "12", g1start: "11905384", g1end: "12043977", g1name: "ETV6", g2chr: "15", g2start: "88420169", g2end: "88799384", g2name: "NTRK3"},
	  {fusion: "EGFR--SEPT14", g1chr: "7", g1start: "55086971", g1end: "55273307", g1name: "EGFR", g2chr: "7", g2start: "55861237", g2end: "55930482", g2name: "SEPT14"},
	  {fusion: "EML4--ALK", g1chr: "2", g1start: "42472644", g1end: "42557344", g1name: "EML4", g2chr: "2", g2start: "29416093", g2end: "30143525", g2name: "ALK"},
	  {fusion: "ABL1--BCR", g1chr: "9", g1start: "133589707", g1end: "133761067", g1name: "ABL1", g2chr: "22", g2start: "23523148", g2end: "23657706", g2name: "BCR"},
	]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``LinkRadius``
    default 140, radius of link circle

- ``LinkFillColor``
    default "#F26223", color of link

- ``LinkWidth``
    default 3, width of link

- ``LinkType``
    default Q, [Q/S/T], type of link

- ``displayLinkAxis``
    default true, [true/false], on/off link axis

- ``LinkAxisColor``
    default "#B8B8B8", color of link axis

- ``LinkAxisWidth``
    default 0.5, width of link axis

- ``LinkAxisPad``
    default 3, pad of link axis

- ``displayLinkLabel``
    default true, [true/false], on/off link label

- ``LinkLabelColor``
    default "red", color of link color

- ``LinkLabelSize``
    default 13, size of link label

- ``LinkLabelPad``
    default 8, pad of link label

**Example**: change data configuration of LINK module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example
     
     - Before
     - After
   
   * - Code change

     - .. code-block:: javascript

          LinkRadius: 140,
          LinkFillColor: "#F26223",
          LinkAxisWidth: 0.5,
          displayLinkLabel: true,
          LinkLabelColor: "red",
          LinkLabelSize: 13,
          LinkLabelPad: 8,

     - .. code-block:: javascript

          LinkRadius: 170,
          LinkFillColor: "red",
          LinkAxisWidth: 3,
          displayLinkLabel: false,
          LinkLabelColor: "red",
          LinkLabelSize: 13,
          LinkLabelPad: 8,

   * - Image change

     - .. image:: _images/API_data_configuration_LINK01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_LINK01_before.html

     - .. image:: _images/API_data_configuration_LINK01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_LINK01_after.html
         
- ``LINKAnimationDisplay``
      default "false", [true/false], open/not open animation event of LINK module
         
- ``LINKAnimationDirection``
      default "1to2", [1to2/2to1], Animation from start chromosome to end chromosome or reverse.

- ``LINKAnimationTime``
      default 2000, specifies the animation time in milliseconds.

- ``LINKAnimationDelay``
      default 20, specifies the animation delay in milliseconds. 

- ``LINKAnimationType``
      default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

**Example**: LINK Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

      - Before
      - After

   * - Code change

      - .. code-block:: javascript

               LinkFillColor: "blue",
               LINKAnimationDisplay:true,
               LINKAnimationDirection:"2to1",
               LINKAnimationTime:1000,
               LINKAnimationDelay:1000,
               LINKAnimationType:"linear",

      - .. code-block:: javascript

               LinkFillColor: "#F26223",
               LINKAnimationDisplay:true,
               LINKAnimationDirection:"1to2",
               LINKAnimationTime:2000,
               LINKAnimationDelay:2000,
               LINKAnimationType:"linear",

   * - Image change

      - .. image:: _images/LINKAnimation01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/LINKAnimation01_before.html
      
      - .. image:: _images/LINKAnimation01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/LINKAnimation01_after.html

``````````````
Part 2 : Data
``````````````

- The 1 column(``name``) is the name of the link.
- The 2 column(``g1chr``) is the chromosome of gene 1.
- The 3 column(``g1start``) is the start of gene 1.
- The 4 column(``g1end``) is the end of gene 1.
- The 5 column(``g1name``) is the name of gene 1.
- The 6 column(``g2chr``) is the chromosome of gene 2.
- The 7 column(``g2start``) is the start of gene 2.
- The 8 column(``g2end``) is the end of gene 2.
- The 9 column(``g2name``) is the name of gene 2.
- The 10 column(``html``) is the html for tooltips.

-------------------
6.4 CNV module
-------------------

.. code-block:: javascript

	var CNV01 = [ "CNV01" , {
	  maxRadius: 175,
	  minRadius: 116,
	  CNVwidth: 2,
	  CNVColor: "#4876FF",
     ValueAxisManualScale:false,
     ValueAxisMaxScale:10,
     ValueAxisMinScale:0,
     strokeColor:"black",
     strokeWidth:1,
     opacity:1,
     CNVAnimationDisplay: false,
     CNVAnimationTime: 2000,
     CNVAnimationDelay: 20,
     CNVAnimationType: "bounce",
	} , [
	  {chr: "1", start: "764788", end: "87109267", value: "2.5",color:"red",html:" "},
	  {chr: "1", start: "87109268", end: "120217058", value: "2",color:"red"},
	  {chr: "1", start: "144101324", end: "222713034", value: "4",color:"red"},
	  {chr: "1", start: "222713035", end: "222867750", value: "6",color:"red"},
	  ......
	  {chr: "9", start: "30330084", end: "140139368", value: "3.5",color:"red"},
	  {chr: "X", start: "105073", end: "114046817", value: "1",color:"red"},
	  {chr: "X", start: "114112404", end: "114299959", value: "2",color:"red"},
	  {chr: "X", start: "114376344", end: "154884814", value: "1",color:"red"},
	]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``maxRadius``
    default 155, max radius to show CNVs with max vlaue

- ``minRadius``
    default 116, min radius to show CNVs with min vlaue

- ``CNVwidth``
    default 2, CNV width

- ``CNVColor``
    default "#4876FF", CNV color
   
- ``ValueAxisManualScale``
   default "false", [false/true], whether manually control the scale of value

- ``ValueAxisMaxScale``
   default "10", the maxmium value manually set for value
   
- ``ValueAxisMaxScale``
   default "0", the minimum value manually set for value
   
- ``strokeColor``
    default "black", stroke color for CNV
   
- ``strokeWidth``
    default 1, stroke width for CNV
   
- ``opacity``
    default 1, opacity rate for CNV

**Example**: change data configuration of CNV module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          CNVwidth: 2,
          CNVColor: "#4876FF",

     - .. code-block:: javascript

          CNVwidth: 4,
          CNVColor: "red",

   * - Image change

     - .. image:: _images/API_data_configuration_CNV01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_CNV01_before.html
     
     - .. image:: _images/API_data_configuration_CNV01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_CNV01_after.html
         
- ``CNVAnimationDisplay``
      default "false", [true/false], open/not open animation event of CNV module

- ``CNVAnimationTime``
      default 2000, specifies the animation time in milliseconds.

- ``CNVAnimationDelay``
      default 20, specifies the animation delay in milliseconds. 

- ``CNVAnimationType``
      default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

**Example**: CNV Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

      - Before
      - After
   
   * - Code change
     
      - .. code-block:: javascript

               CNVColor: "red",
               CNVAnimationDisplay: true,
               CNVAnimationTime: 1000,
               CNVAnimationDelay: 20,
               CNVAnimationType: "linear",

      - .. code-block:: javascript

               CNVColor: "#4876FF",
               CNVAnimationDisplay: true,
               CNVAnimationTime: 2000,
               CNVAnimationDelay: 20,
               CNVAnimationType: "bounce", 

   * - Image change
      
      - .. image:: _images/CNVAnimation01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/CNVAnimation01_before.html
      
      - .. image:: _images/CNVAnimation01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/CNVAnimation01_after.html

``````````````
Part 2 : Data
``````````````

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``start``) is the start of the CNV region.
- The 3 column(``end``) is the end of the CNV region.
- The 4 column(``value``) is the copy number of CNV region.
- The 5 column(``color``) is the specific color of CNV region.
- The 6 column(``html``) is the html for tooltips.

-------------------
6.5 ARC module
-------------------

.. code-block:: javascript

	var ARC01 = [ "ARC01" , {
	  innerRadius: -55,
	  outerRadius: -45,
     ARCAnimationDisplay: false,
     ARCAnimationTime: 2000,
     ARCAnimationDelay: 20,
     ARCAnimationType: "bounce",
     ARCOpacity:1,
	} , [
	  {chr: "EGFR", start: "57", end: "167", color: "#CD8500", des: "Recep_L domain",html:" "},
	  {chr: "EGFR", start: "185", end: "338", color: "blue", des: "Furin-like domain"},
	  {chr: "EGFR", start: "361", end: "480", color: "#CD8500", des: "Recep_L domain"},
	  {chr: "EGFR", start: "505", end: "636", color: "yellow", des: "GF_recep_IV domain"},
	  {chr: "EGFR", start: "713", end: "965", color: "red", des: "Pkinase Tyr domain"},
	]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``innerRadius``
    default -55, inner radius of arc

- ``outerRadius``
    default -45, outer radius of arc

- ``ARCOpacity``
    default 1, opacity of arc

**Example**: change data configuration of ARC module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example
     
     - Before  
     - After
   
   * - Code change
     
     - .. code-block:: javascript

          innerRadius: -55,
          outerRadius: -45,

     - .. code-block:: javascript

          innerRadius: 8,
          outerRadius: -8,

   * - Image change
     
     - .. image:: _images/API_data_configuration_ARC01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_ARC01_before.html
     
     - .. image:: _images/API_data_configuration_ARC01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_ARC01_after.html
         
- ``ARCAnimationDisplay``
      default "false", [true/false], open/not open animation event of ARC module

- ``ARCAnimationTime``
      default 2000, specifies the animation time in milliseconds.

- ``ARCAnimationDelay``
      default 20, specifies the animation delay in milliseconds. 

- ``ARCAnimationType``
      default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

**Example**: ARC Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example
      
      - Before   
      - After
   
   * - Code change
      
      - .. code-block:: javascript

               ARCAnimationDisplay: true,
               ARCAnimationTime: 2000,
               ARCAnimationDelay: 500,
               ARCAnimationType: "bounce",

      - .. code-block:: javascript

               ARCAnimationDisplay: true,
               ARCAnimationTime: 1000,
               ARCAnimationDelay: 500,
               ARCAnimationType: "linear",

   * - Image change
      
      - .. image:: _images/ARCAnimation01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/ARCAnimation01_before.html
      
      - .. image:: _images/ARCAnimation01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/ARCAnimation01_after.html

``````````````
Part 2 : Data
``````````````

- The 1 column(``chr``) is the name of the chromosome. In this example, this field specify the protein name.
- The 2 column(``start``) is the start of the arc.
- The 3 column(``end``) is the end of the arc.
- The 4 column(``color``) is the color of the arc.
- The 5 column(``des``) is the description of the arc.
- The 6 column(``html``) is the html for tooltips.

-------------------
6.6 HEATMAP module
-------------------

.. code-block:: javascript

	var HEATMAP01 = [ "HEATMAP01" , {
	  innerRadius: -25,
	  outerRadius: -65,
	  maxColor: "red",
	  minColor: "yellow",
     totalLayer:1,
     ValueAxisManualScale:false,
     ValueAxisMaxScale:10,
     ValueAxisMinScale:0,
     HEATMAPAnimationDisplay: false,
     HEATMAPAnimationDirection:"O2I", 
     HEATMAPAnimationColorDirection:"L2C", 
     HEATMAPAnimationTime: 2000,
     HEATMAPAnimationDelay: 20,
     HEATMAPAnimationType: "bounce",  
	} , [
	  {chr: "2L", start: "1", end: "1011544", name: "test heatmap", value: "0.8",layer:"1",html:" "},
	  {chr: "2L", start: "1011548", end: "2011544", name: "test heatmap", value: "0.3",layer:"1"},
	  {chr: "2L", start: "2011548", end: "3011544", name: "test heatmap", value: "0.1",layer:"1"},
	  {chr: "2L", start: "2011545", end: "2011546", name: "test heatmap", value: "0.01",layer:"1"},
	......
	  {chr: "X", start: "18011548", end: "19011544", name: "test heatmap", value: "0.83",layer:"1"},
	  {chr: "X", start: "19011548", end: "20011544", name: "test heatmap", value: "0.39",layer:"1"},
	  {chr: "X", start: "20011548", end: "21146708", name: "test heatmap", value: "0.49",layer:"1"},
	  {chr: "X", start: "21011548", end: "22422827", name: "test heatmap", value: "0.83",layer:"1"},
	]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``innerRadius``
    default -25, inner radius of heatmap

- ``outerRadius``
    default -65, outer radius of heatmap

- ``maxColor``
    default "red", color to show max value in heatmap

- ``minColor``
    default "yellow", color to show min value in heatmap
   
- ``totalLayer``
    default "1", total layers of all values in heatmap
   
- ``ValueAxisManualScale``
   default "false", [false/true], whether manually control the scale of value

- ``ValueAxisMaxScale``
   default "10", the maxmium value manually set for value
   
- ``ValueAxisMaxScale``
   default "0", the minimum value manually set for value

**Example**: change data configuration of HEATMAP module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example
     
     - Before
     - After
   
   * - Code change
     
     - .. code-block:: javascript

          innerRadius: -25,
          outerRadius: -65,
          maxColor: "red",
          minColor: "yellow"

     - .. code-block:: javascript

          innerRadius: -65,
          outerRadius: -115,
          maxColor: "red",
          minColor: "green"

   * - Image change
     - .. image:: _images/API_data_configuration_HEATMAP01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_HEATMAP01_before.html
     
     - .. image:: _images/API_data_configuration_HEATMAP01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_HEATMAP01_after.html
         
- ``HEATMAPAnimationDisplay``
      default "false", [true/false], open/not open animation event of HEATMAP module
      
- ``HEATMAPAnimationDirection``
      default "O2I", [O2I/I2O], animation from outside to inside or from inside to outside
      
- ``HEATMAPAnimationColorDirection``
      default "L2C", [L2C/H2C], color animation from highest(max) color to customized color or from lowest(min) color to customized color.

- ``HEATMAPAnimationTime``
      default 2000, specifies the animation time in milliseconds.

- ``HEATMAPAnimationDelay``
      default 20, specifies the animation delay in milliseconds. 

- ``HEATMAPAnimationType``
      default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

**Example**: HEATMAP Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

      - Before
      - After
   
   * - Code change
   
      - .. code-block:: javascript

               maxColor: "darkblue",
               minColor: "lightgreen",
               HEATMAPAnimationDisplay:true,
               HEATMAPAnimationType:"linear",

      - .. code-block:: javascript

               maxColor: "red",
               minColor: "yellow",
               HEATMAPAnimationDisplay:true,
               HEATMAPAnimationType:"bounce",

   * - Image change
   
      - .. image:: _images/HEATMAPAnimation01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/HEATMAPAnimation01_before.html
      
      - .. image:: _images/HEATMAPAnimation01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/HEATMAPAnimation01_after.html

``````````````
Part 2 : Data
``````````````

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``start``) is the start of the region.
- The 3 column(``end``) is the end of the region.
- The 4 column(``name``) is the name of the region.
- The 5 column(``value``) is the value of the region.
- The 6 column(``layer``) is the specific layer of the region.
- The 7 column(``html``) is the html for tooltips.

---------------------
6.7 HISTOGRAM module
---------------------

.. code-block:: javascript

	var HISTOGRAM01 = [ "HISTOGRAM01" , {
	  maxRadius: 220,
	  minRadius: 185,
	  histogramFillColor: "#FF6666",
     ValueAxisManualScale:false,
     ValueAxisMaxScale:10,
     ValueAxisMinScale:0,
     HISTOGRAMAnimationDisplay: false,
     HISTOGRAMAnimationDirection:"O2I", //O2I,I2O  [out to in/in to out]
     HISTOGRAMAnimationTime: 2000,
     HISTOGRAMAnimationDelay: 20,
	} , [
	  {chr: "2L", start: "1", end: "1011544", name: "test histogram", value: "0.8",html:" "},
	  {chr: "2L", start: "1011548", end: "2011544", name: "test histogram", value: "0.3"},
	  {chr: "2L", start: "2011548", end: "3011544", name: "test histogram", value: "0.1"},
	  {chr: "2L", start: "2011545", end: "2011546", name: "test histogram", value: "0.01"},
	  ......
	  {chr: "X", start: "18011548", end: "19011544", name: "test histogram", value: "0.83"},
	  {chr: "X", start: "19011548", end: "20011544", name: "test histogram", value: "0.39"},
	  {chr: "X", start: "20011548", end: "21146708", name: "test histogram", value: "0.49"},
	  {chr: "X", start: "21011548", end: "22422827", name: "test histogram", value: "0.83"},
	]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``maxRadius``
    default 240, max radius to show HISTOGRAM with max vlaue

- ``minRadius``
    default 205, min radius to show HISTOGRAM with min vlaue

- ``histogramFillColor``
    default "#FF6666", color of histogram
   
- ``ValueAxisManualScale``
   default "false", [false/true], whether manually control the scale of value

- ``ValueAxisMaxScale``
   default "10", the maxmium value manually set for value
   
- ``ValueAxisMaxScale``
   default "0", the minimum value manually set for value

**Example**: change data configuration of HISTOGRAM module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After
   
   * - Code change
   
     - .. code-block:: javascript

          maxRadius: 220,
          minRadius: 185,
          histogramFillColor: "#FF6666",

     - .. code-block:: javascript

          maxRadius: 170,
          minRadius: 135,
          histogramFillColor: "green",

   * - Image change
   
     - .. image:: _images/API_data_configuration_HISTOGRAM01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_HISTOGRAM01_before.html
     
     - .. image:: _images/API_data_configuration_HISTOGRAM01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_HISTOGRAM01_after.html

- ``HISTOGRAMAnimationDisplay``
      default "false", [true/false], open/not open animation event of HISTOGRAM module

- ``HISTOGRAMAnimationDirection``
      default "O2I", [O2I/I2O], animation from outside to inside or from inside to outside

- ``HISTOGRAMAnimationTime``
      default 2000, specifies the animation time in milliseconds.

- ``HISTOGRAMAnimationDelay``
      default 20, specifies the animation delay in milliseconds. 

**Example**: HISTOGRAM Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

      - Before
      - After
   
   * - Code change
   
      - .. code-block:: javascript

               histogramFillColor: "#d14799",
               HISTOGRAMAnimationDisplay: true,
               HISTOGRAMAnimationDirection:"I2O", //O2I,I2O  [out to in/in to out]
               HISTOGRAMAnimationTime: 2000,
               HISTOGRAMAnimationDelay: 20,

      - .. code-block:: javascript

               histogramFillColor: "#FF6666",
               HISTOGRAMAnimationDisplay: true,
               HISTOGRAMAnimationDirection:"O2I", //O2I,I2O  [out to in/in to out]
               HISTOGRAMAnimationTime: 100,
               HISTOGRAMAnimationDelay: 20,

   * - Image change
   
      - .. image:: _images/HISTOGRAMAnimation01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/HISTOGRAMAnimation01_before.html
      
      - .. image:: _images/HISTOGRAMAnimation01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/HISTOGRAMAnimation01_after.html

``````````````
Part 2 : Data
``````````````

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``start``) is the start of the region.
- The 3 column(``end``) is the end of the region.
- The 4 column(``name``) is the name of the region.
- The 5 column(``value``) is the value of the region.
- The 6 column(``html``) is the html for tooltips.

-------------------
6.8 LINE module
-------------------

.. code-block:: javascript

	var LINE01 = [ "LINE01" , {
	  maxRadius: 220,
	  minRadius: 170,
	  LineColor: "#EEAD0E",
	  LineWidth: 2,
     ValueAxisManualScale:false,
     ValueAxisMaxScale:10,
     ValueAxisMinScale:0,
     LineType:"cardinal", //linear,cardinal,basis,monotone
     LINEAnimationDisplay: false,
     LINEAnimationDirection:"S2E", //S2E,E2S  [start to end/end to start]
     LINEAnimationTime: 2000,
     LINEAnimationDelay: 20,
     LINEAnimationType: "bounce",  //linear,circle,elastic,bounce

	} , [
	  {chr: "1", pos: "813468", value: "0.5",html:" "},
	  {chr: "1", pos: "3383745", value: "0.22385"},
	  {chr: "1", pos: "6157646", value: "0.238643"},
	  {chr: "1", pos: "24793116", value: "0.876947"},
	  ......
	  {chr: "X", pos: "136860114", value: "0.267261"},
	  {chr: "X", pos: "138413104", value: "0.847613"},
	  {chr: "X", pos: "149344414", value: "0.830811"},
	  {chr: "X", pos: "154203563", value: "0.43466"},
	]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``maxRadius``
    default 220, max radius to show LINE with max vlaue

- ``minRadius``
    default 170, min radius to show LINE with min vlaue

- ``LineFillColor``
    default "#EEAD0E", color of line

- ``LineWidth``
    default 2, width of line
   
- ``LineType``
   default "cardinal", \[cardinal/linear/basis/monotone\] ,line type
   
- ``ValueAxisManualScale``
   default "false", [false/true], whether manually control the scale of value

- ``ValueAxisMaxScale``
   default "10", the maxmium value manually set for value
   
- ``ValueAxisMaxScale``
   default "0", the minimum value manually set for value


**Example**: change data configuration of LINE module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After
   
   * - Code change
   
     - .. code-block:: javascript

          LineColor: "#EEAD0E",
          LineWidth: 2,

     - .. code-block:: javascript

          LineColor: "green",
          LineWidth: 1,

   * - Image change
   
     - .. image:: _images/API_data_configuration_LINE01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_LINE01_before.html
     
     - .. image:: _images/API_data_configuration_LINE01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_LINE01_after.html
         
- ``LINEAnimationDisplay``
      default "false", [true/false], open/not open animation event of LINE module
         
- ``LINEAnimationDirection``
      default "S2E", [S2E/E2S], animation from start to end or from end to start

- ``LINEAnimationTime``
      default 2000, specifies the animation time in milliseconds.

- ``LINEAnimationDelay``
      default 20, specifies the animation delay in milliseconds. 

- ``LINEAnimationType``
      default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

**Example**: LINE Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

      - Before
      - After
   
   * - Code change
   
      - .. code-block:: javascript

               LineColor: "#65662c",
               LINEAnimationDisplay: true,
               LINEAnimationDirection:"S2E",
               LINEAnimationTime: 2000,
               LINEAnimationDelay: 2000,
               LINEAnimationType: "linear",

      - .. code-block:: javascript

               LineColor: "#9932CC",
               LINEAnimationDisplay: true,
               LINEAnimationDirection:"E2S",
               LINEAnimationTime: 2000,
               LINEAnimationDelay: 2000,
               LINEAnimationType: "linear",

   * - Image change
   
      - .. image:: _images/LINEAnimation01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/LINEAnimation01_before.html
      
      - .. image:: _images/LINEAnimation01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/LINEAnimation01_after.html

``````````````
Part 2 : Data
``````````````

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``pos``) is the position of the point.
- The 3 column(``value``) is the value of the point.
- The 4 column(``html``) is the html for tooltips.

----------------------
6.9 BACKGROUND module
----------------------

.. code-block:: html

	<script>
	var BACKGROUND01 = [ "BACKGROUND01" , {
	  BginnerRadius: 230,
	  BgouterRadius: 200,
	  BgFillColor: "#F2F2F2",
	  BgborderColor : "#000",
	  BgborderSize : 0.3,
	  axisShow: "true",
	  axisWidth: 0.1,
	  axisColor: "#000",
     axisOpacity: 0.5,
	  axisNum: 8,
    BACKGROUNDAnimationDisplay: false,
    BACKGROUNDAnimationTime: 2000,
    BACKGROUNDAnimationDelay: 20,
    BACKGROUNDAnimationType: "bounce",
	}];
	</script>

```````````````````````
Part 1 : Configuration
```````````````````````

- ``BginnerRadius``
    default 230, inner radius of background

- ``BgouterRadius``
    default 200, outer radius of background

- ``BgFillColor``
    default "#F2F2F2", color of background

- ``BgborderColor``
    default "#000", color of background border

- ``BgborderSize``
    default 0.3, size of background border

- ``axisShow``
    default false, [true/false], on/off background axis

- ``axisWidth``
    default 0.1, width of axis

- ``axisColor``
    default "#000", color of background axis

- ``axisOpacity``
    default 0.5, opacity of axis

- ``axisNum``
    default 8, number of axis

**Example**: change data configuration of BACKGROUND module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After
   
   * - Code change
   
     - .. code-block:: javascript

          BginnerRadius: 200,
          BgouterRadius: 150,
          BgborderSize : 0.3,
          axisShow: "false",
          axisWidth: 0.1,
          axisColor: "#000",
          axisNum: 8

     - .. code-block:: javascript

          BginnerRadius: 190,
          BgouterRadius: 100,
          BgborderSize : 0.4,
          axisShow: "true",
          axisWidth: 0.2,
          axisColor: "red",
          axisNum: 5

   * - Image change
   
     - .. image:: _images/API_data_configuration_BACKGROUND01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_BACKGROUND01_before.html
     
     - .. image:: _images/API_data_configuration_BACKGROUND01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_BACKGROUND01_after.html

- ``BACKGROUNDAnimationDisplay``
      default "false", [true/false], open/not open animation event of BACKGROUND module.

- ``BACKGROUNDAnimationTime``
      default 2000, specifies the animation time in milliseconds.

- ``BACKGROUNDAnimationDelay``
      default 20, specifies the animation delay in milliseconds. 

- ``BACKGROUNDAnimationType``
      default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

-------------------
6.10 TEXT module
-------------------

.. code-block:: html

	<script>
	  var TEXT01 = [ "TEXT01" , {
	     x: -20,
	     y: 0,
	     textSize: 20,
	     textWeight: "bold",
	     textColor: "red",
	     textOpacity: 1.0,
        rotateRate:0,
	     text: "EGFR",
       TEXTAnimationDisplay:false,
       TEXTAnimationInitialSize:20,
       TEXTAnimationInitialWeight:"bold",
       TEXTAnimationInitialColor:"black",
       TEXTAnimationInitialOpacity:1,
       TEXTAnimationInitialPositionX:0,
       TEXTAnimationInitialPositionY:0,
       TEXTAnimationInitialRotate:0,
       TEXTAnimationDelay:50,
       TEXTAnimationTime:1000,
       TEXTAnimationType:"linear",
	  }];
	</script>

```````````````````````
Part 1 : Configuration
```````````````````````

- ``x``
    default -20, x of text

- ``y``
    default 0, y of text

- ``textSize``
    default 20, font-size of text

- ``textWeight``
    default "bold", normal,bold,bolder,lighter,100,200,300,400,500,600,700,800,900

- ``textColor``
    default "red", color of text

- ``textOpacity``
    default 1.0, opacity of text
   
- ``rotateRate``
    default 0, [-1,1] rotate rate for text

- ``textSize``
    default "TEXT", text content

**Example**: change data configuration of TEXT module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

          x: -20,
          y: 0,
          textSize: 20,
          textWeight: "bold",
          textColor: "red",
          textOpacity: 1.0,
          text: "EGFR"

     - .. code-block:: javascript

          x: -60,
          y: 1,
          textSize: 18,
          textWeight: "300",
          textColor: "green",
          textOpacity: 0.9,
          text: "EGFR - Mutations"

   * - Image change

     - .. image:: _images/API_data_configuration_TEXT01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_TEXT01_before.html
     
     - .. image:: _images/API_data_configuration_TEXT01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_data_configuration_TEXT01_after.html

- ``TEXTAnimationDisplay``
      default "false", [true/false], open/not open animation event of TEXT module.

- ``TEXTAnimationInitialSize``
      default 20, initial size of text.

- ``TEXTAnimationInitialWeight``
      default "bold", [normal,bold,bolder,lighter,100,200,300,400,500,600,700,800,900], initial weight of text.

- ``TEXTAnimationInitialOpacity``
      default 1, initial opacity of text.

- ``TEXTAnimationInitialPositionX``
      default 0, initial X axis position of text.

- ``TEXTAnimationInitialPositionY``
      default 0, initial Y axis position of text.

- ``TEXTAnimationInitialRotate``
      default 0, initial rotate rate of text.

- ``TEXTAnimationTime``
      default 1000, specifies the animation time in milliseconds.

- ``TEXTAnimationDelay``
      default 50, specifies the animation delay in milliseconds. 

- ``TEXTAnimationType``
      default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

-------------------
6.11 WIG module
-------------------

.. code-block:: javascript

	var WIG01 = [ "WIG01" , {
      maxRadius: 200,
      minRadius: 150,
      direction:"out",
      WIGStrokeColor: "#3D6390",
      WIGColor: "#3D6390",
      WIGStrokeWidth:1,
      WIGOpacity:1,
      WIGStrokeType:"cardinal", //linear,cardinal,basis,monotone
      ValueAxisManualScale:false,
      ValueAxisMaxScale:10,
      ValueAxisMinScale:0,
      WIGAnimationDisplay: false,
      WIGAnimationTime: 2000,
      WIGAnimationDelay: 20,
      WIGAnimationType: "bounce", 
      } , [
      {chr:"chr8",pos:"0.09827044025157233",value:"0.0199",html:" "},
      {chr:"chr8",pos:"1.3266509433962264",value:"0.0199"},
      {chr:"chr8",pos:"2.5550314465408803",value:"0.0199"},
      {chr:"chr8",pos:"3.7834119496855347",value:"0.0498"},
      ......
      {chr:"chr8",pos:"996.314858490566",value:"0.0299"},
      {chr:"chr8",pos:"997.5432389937107",value:"0.0398"},
      {chr:"chr8",pos:"998.7716194968554",value:"0.0896"},
      {chr:"chr8",pos:"1000.0",value:"0.1195"},
   ]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``maxRadius``
      default 220, max radius to show WIG with max vlaue

- ``minRadius``
      default 170, min radius to show WIG with min vlaue

- ``direction``
      default "out", [out/in], the direction of this WIG module

- ``WIGStrokeColor``
      default "black", color of the stroke

- ``WIGColor``
      default "red", color of fill area

- ``WIGStrokeWidth``
      default 1, width of the stroke
      
- ``WIGOpacity``
      default 1, opacity rate of area

- ``WIGStrokeType``
      default "cardinal", [cardinal/linear/basis/monotone] ,stroke type
      
- ``ValueAxisManualScale``
   default "false", [false/true], whether manually control the scale of value

- ``ValueAxisMaxScale``
   default "10", the maxmium value manually set for value
   
- ``ValueAxisMaxScale``
   default "0", the minimum value manually set for value


**Example**: change data configuration of WIG module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

               WIGColor: "#EEAD0E",
               WIGStrokeType: "cardinal",

     - .. code-block:: javascript

               WIGColor: "green",
               WIGStrokeType: "basis",

   * - Image change

     - .. image:: _images/API_data_configuration_WIG01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_WIG01_before.html
     
     - .. image:: _images/API_data_configuration_WIG01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_WIG01_after.html
               
- ``WIGAnimationDisplay``
      default "false", [true/false], open/not open animation event of WIG module

- ``WIGAnimationTime``
      default 2000, specifies the animation time in milliseconds.

- ``WIGAnimationDelay``
      default 20, specifies the animation delay in milliseconds. 

- ``WIGAnimationType``
      default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

**Example**: WIG Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

      - Before
      - After

   * - Code change

      - .. code-block:: javascript

               WIGStrokeColor: "#68bc45",
               WIGColor: "#68bc45",
               WIGAnimationDisplay: true,
               WIGAnimationTime: 2000,
               WIGAnimationDelay: 20,
               WIGAnimationType: "bounce",
               
      - .. code-block:: javascript

               WIGStrokeColor: "#3D6390",
               WIGColor: "#3D6390",
               WIGAnimationDisplay: true,
               WIGAnimationTime: 2000,
               WIGAnimationDelay: 20,
               WIGAnimationType: "linear",

   * - Image change

      - .. image:: _images/WIGAnimation01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/WIGAnimation01_before.html
      
      - .. image:: _images/WIGAnimation01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/WIGAnimation01_after.html

``````````````
Part 2 : Data
``````````````

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``pos``) is the position of the point.
- The 3 column(``value``) is the value of the point.  
- The 4 column(``html``) is the html for tooltips.       
         
---------------------
6.12 LOLLIPOP module
---------------------

.. code-block:: javascript

	var LOLLIPOP01 = [ "LOLLIPOP01" , {
      LOLLIPOPFillColor:"#9400D3",
      LOLLIPOPSecondColor: "#FFFFFF",
      PointType: "circle",
      circleSize: 6,
      diamondWidth:10,
      diamondHeight:5,
      rectWidth: 2,
      rectHeight: 2,
      stroke:true,
      strokeColor: "#999999",
      strokeWidth: "1px",
      lineAutoHeight: true,
      lineAutoMaximumHeightZoomRate:1,
      lineHeightRate:0.75,
      ValueAxisManualScale:false,
      ValueAxisMaxScale:10,
      ValueAxisMinScale:0,
      LOLLIPOPAnimationDisplay: false,
      LOLLIPOPAnimationTime: 2000,
      LOLLIPOPAnimationDelay: 20,
      LOLLIPOPAnimationType: "bounce", 
      LOLLIPOPLineWidth: 1,
      LOLLIPOPLineColor: "#000000",
      realStart: 101219350,
   } , [
      {protein: "EGFR", chr: "7", pos: "101219410", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero",html:" "},
      {protein: "EGFR", chr: "7", pos: "101219417", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101219425", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101219431", strand: "+", CancerTypeNumber: "3", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      ......
      {protein: "EGFR", chr: "7", pos: "101220278", strand: "+", CancerTypeNumber: "3", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero"},
      {protein: "EGFR", chr: "7", pos: "101220281", strand: "+", CancerTypeNumber: "2", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101220288", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Homo"},
      {protein: "EGFR", chr: "7", pos: "101220295", strand: "+", CancerTypeNumber: "1", AA_pos: "AA_858", AA_change: "L/R", Consequence: "missense_variant", color: "#FEFF00", type: "Hetero"},
   ]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``LOLLIPOPFillColor``
      default "red", fill color for LOLLIPOP

- ``LOLLIPOPSecondColor``
      default "white", another fill color for heterogeneous LOLLIPOP

- ``PointType``
      default "circle", [circle/rect/diamond], type for LOLLIPOP point

- ``circleSize``
      default 2, size for circle LOLLIPOP

- ``diamondWidth``
      default 10, width for diamond LOLLIPOP
      
- ``diamondHeight``
      default 5, height for diamond LOLLIPOP
      
- ``rectWidth``
      default 2, width for rect LOLLIPOP
      
- ``rectHeight``
   default 2, height for rect LOLLIPOP

- ``stroke``
   default true, [true/false], whether display stroke for LOLLIPOP or not
   
- ``strokeColor``
   default "#000000", color for stroke
   
- ``strokeWidth``
   default "0.5px", width for stroke
   
- ``lineAutoHeight``
   default true, [true/false], whether define the line height of LOLLIPOP automatically by CancerTypeNumber or not

- ``lineAutoMaximumHeightZoomRate``
   default 1, Zoom rate of line height of LOLLIPOP(only for auto height)
   
- ``lineHeightRate``
   default 0.75, all LOLLIPOP share the same height based on the maximum height
   
- ``LOLLIPOPLineWidth``
   default 2, the width of LOLLIPOP line
   
- ``LOLLIPOPLineColor``
   default "#000000", the color of LOLLIPOP line
   
- ``realStart``
   default 0, the real start of the genome. For example, if you set your genome length which is 1000, while you data using the real position, which is from 1000000 to 1001000, you can set realStart at 1000000 so that you don't need to modify your data.
   
- ``ValueAxisManualScale``
   default "false", [false/true], whether manually control the scale of value

- ``ValueAxisMaxScale``
   default "10", the maxmium value manually set for value
   
- ``ValueAxisMaxScale``
   default "0", the minimum value manually set for value

**Example**: change data configuration of LOLLIPOP module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

               LOLLIPOPFillColor:"#9400D3",
               LOLLIPOPSecondColor: "#FFFFFF",
               PointType: "circle",
               circleSize: 6,

     - .. code-block:: javascript

               LOLLIPOPFillColor:"blue",
               LOLLIPOPSecondColor: "green",
               PointType: "diamond",
               diamondWidth:20,
               diamondHeight:10,
               
   * - Image change

     - .. image:: _images/API_data_configuration_LOLLIPOP01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_LOLLIPOP01_before.html
     
     - .. image:: _images/API_data_configuration_LOLLIPOP01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_LOLLIPOP01_after.html

- ``LOLLIPOPAnimationDisplay``
   default false, [true/false], open or not open animation display
   
- ``LOLLIPOPAnimationTime``
   default 2000, animation time for LOLLIPOP
   
- ``LOLLIPOPAnimationDelay``
   default 20, delay time before animation
   
- ``LOLLIPOPAnimationType``
   default "bounce", [linear/circle/elastic/bounce], type of animation
   
**Example**: LOLLIPOP Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

               LOLLIPOPAnimationDisplay: true,
               LOLLIPOPAnimationTime: 2000,
               LOLLIPOPAnimationDelay: 20,
               LOLLIPOPAnimationType: "bounce", 

     - .. code-block:: javascript

               LOLLIPOPAnimationDisplay: true,
               LOLLIPOPAnimationTime: 4000,
               LOLLIPOPAnimationDelay: 40,
               LOLLIPOPAnimationType: "linear", 

   * - Image change

     - .. image:: _images/LOLLIPOPAnimation01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/LOLLIPOPAnimation01_before.html
     
     - .. image:: _images/LOLLIPOPAnimation01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/LOLLIPOPAnimation01_after.html   

``````````````
Part 2 : Data
``````````````

- The 1 column(``protein``) is the name of the protein.
- The 2 column(``chr``) is the name of the chromosome.
- The 3 column(``pos``) is the position of the point. 
- The 4 column(``strand``) is the strand of the protein.
- The 5 column(``CancerTypeNumber``) is the cancer type number this point are found.
- The 6 column(``AA_pos``) is the AA position of the point. 
- The 7 column(``AA_change``) is the AA change of the chromosome.
- The 8 column(``Consequence``) is the Consequence of the point.
- The 9 column(``color``) is the color of the point. 
- The 10 column(``type``) is the type of the point, whether homogeneous or heterogeneous.  
- The 11 column(``html``) is the html for tooltips.          

-------------------
6.13 GENE module
-------------------

.. code-block:: javascript

	var GENE01 = [ "GENE01" , {
      outerRadius: -25,
      innerRadius: -10,
      pathColor:"black",
      pathWidth:1,
      arrow:true,
      arrowGap: 2,
      arrowColor: "blue",
      arrowSize: "12px",
      cdsColor: "blue",
      cdsStrokeColor: "blue",
      cdsStrokeWidth: 1,
      utrWidth: -5,
      utrColor: "blue",
      utrStrokeColor: "blue",
      utrStrokeWidth: 1,
      GENEAnimationDisplay: false,
      GENEAnimationTime: 2000,
      GENEAnimationDelay: 20,
      GENEAnimationType: "bounce",
      } , [
      {chr: "EGFR", strand: "+", start: "57", end: "965", type: "gene", name: "EGFR", link: "https://www.intogen.org/search?gene=EGFR",html:" "},
      {chr: "EGFR", strand: "+", start: "57", end: "167", type: "cds", name: "EGFR", link: "https://www.intogen.org/search?gene=EGFR"},
      {chr: "EGFR", strand: "+", start: "185", end: "338", type: "cds", name: "EGFR", link: "https://www.intogen.org/search?gene=EGFR"},
      {chr: "EGFR", strand: "+", start: "361", end: "480", type: "cds", name: "EGFR", link: "https://www.intogen.org/search?gene=EGFR"},
      {chr: "EGFR", strand: "+", start: "505", end: "636", type: "cds", name: "EGFR", link: "https://www.intogen.org/search?gene=EGFR"},
      {chr: "EGFR", strand: "+", start: "713", end: "965", type: "cds", name: "EGFR", link: "https://www.intogen.org/search?gene=EGFR"},
   ]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``outerRadius``
      default -10, outer radius compared to genome radius

- ``innerRadius``
      default -30, inner radius compared to genome radius
      
- ``pathColor``
      default "black", color for gene path
      
- ``pathWidth``
      default 1, width for gene path
      
- ``arrow``
      default true, [true/false], whether display arrow on gene path or not

- ``arrowGap``
      default 2, the gap between arrows in GENE
      
- ``arrowColor``
   default "blue", the color of arrows in GENE
         
- ``arrowSize``
   default "12px", the size of arrows in GENE

- ``cdsColor``
      default "blue", color of cds in GENE
      
- ``cdsStrokeColor``
   default "blue", color of cds stroke in GENE
         
- ``cdsStrokeWidth``
   default 1, stroke width of cds in GENE

- ``utrWidth``
      default -5, width of utr
      
- ``utrColor``
   default "blue", color of utr
         
- ``utrStrokeColor``
   default "blue", color of utr stroke
            
- ``utrStrokeWidth``
   default 1, stroke width of utr

**Example**: change data configuration of GENE module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change
     - .. code-block:: javascript

               outerRadius: -25,
               innerRadius: -10,
               arrowGap: 2,
               arrowColor: "blue",
               arrowSize: "12px",

     - .. code-block:: javascript

               outerRadius: -45,
               innerRadius: -30,
               arrowGap: 1,
               arrowColor: "green",
               arrowSize: "8px",

   * - Image change

     - .. image:: _images/API_data_configuration_GENE01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_GENE01_before.html
     
     - .. image:: _images/API_data_configuration_GENE01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_GENE01_after.html
               
- ``GENEAnimationDisplay``
      default "false", [true/false], open/not open animation event of GENE module

- ``GENEAnimationTime``
      default 2000, specifies the animation time in milliseconds.

- ``GENEAnimationDelay``
      default 20, specifies the animation delay in milliseconds. 

- ``GENEAnimationType``
      default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

**Example**: GENE Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

      - Before
      - After

   * - Code change

      - .. code-block:: javascript

               arrowColor: "green",
               cdsColor: "green",
               cdsStrokeColor: "green",
               GENEAnimationDisplay:true,
               GENEAnimationType:"bounce",
               GENEAnimationTime:1000,
               GENEAnimationDelay:50,

      - .. code-block:: javascript

               arrowColor: "blue",
               cdsColor: "blue",
               cdsStrokeColor: "blue",
               GENEAnimationDisplay:true,
               GENEAnimationType:"linear",
               GENEAnimationTime:1000,
               GENEAnimationDelay:50,


   * - Image change

      - .. image:: _images/GENEAnimation01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/GENEAnimation01_before.html
      
      - .. image:: _images/GENEAnimation01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/GENEAnimation01_after.html
               
``````````````
Part 2 : Data
``````````````

- The 1 column(``chr``) is the chromosome of the gene belong to.
- The 2 column(``strand``) is the strand of the gene.
- The 3 column(``start``) is the start position of the gene.
- The 4 column(``end``) is the end position of the gene.
- The 5 column(``type``) is the type of this sequence [gene/cds/utr].
- The 6 column(``name``) is the name of this sequence.
- The 7 column(``link``) is the hyper link of this sequence.
- The 8 column(``html``) is the html for tooltips.
               
-------------------
6.14 CHORD module
-------------------

.. code-block:: javascript

	var CHORD01 = [ "CHORD01" , {
      CHORDinnerRadius: 237,
      CHORDouterRadius: 238,
      CHORDFillOpacity:0.67,
      CHORDStrokeColor: "black",
      CHORDStrokeWidth: 1,
      CHORDPadding:0.06,
      CHORDAutoFillColor: true,
      CHORDouterARC:true,
      CHORDouterARCAutoColor:true,
      CHORDouterARCText:false,
   } , [
   ['C.CK', 'C.NPK', 'GC.CK', 'GC.NPK', 'Alphaproteobacteria', 'Betaproteobacteria', 'Gammaproteobacteria', 'Deltaproteobacteria', 'Acidobacteria', 'Actinobacteria', 'Bacteroidetes', 'Chloroflexi', 'Firmicutes', 'Gemmatimonadetes', 'Planctomycetes', 'Thaumarchaeota', 'Verrucomicrobia', 'Ascomycota', 'Basidiomycota', 'Zygomycota'],
   [[0, 0, 0, 0, 18.01, 5.72, 5.74, 6.55, 13.38, 20.04, 5.01, 3.63, 2.37, 6.34, 4.35, 1.51, 1.9, 51.72, 24.75, 18.49], [0, 0, 0, 0, 16.12, 5.75, 5.85, 5.67, 16.88, 15.95, 5.24, 3.74, 2.34, 6.97, 6.15, 1.21, 2.37, 40.28, 24.18, 29.3], [0, 0, 0, 0, 16.16, 6.51, 7.82, 5.13, 13.29, 13.11, 7.32, 4.81, 1.52, 7.92, 4.95, 1.52, 2.57, 33.85, 17.93, 41.7], [0, 0, 0, 0, 19.87, 5.53, 6.1, 5.93, 10.07, 23.23, 4.84, 2.9, 4.49, 5.14, 3.81, 1.91, 1.46, 33.56, 12.87, 49.8], [18.01, 16.12, 16.16, 19.87, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [5.72, 5.75, 6.51, 5.53, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [5.74, 5.85, 7.82, 6.1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [6.55, 5.67, 5.13, 5.93, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [13.38, 16.88, 13.29, 10.07, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [20.04, 15.95, 13.11, 23.23, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [5.01, 5.24, 7.32, 4.84, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [3.63, 3.74, 4.81, 2.9, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [2.37, 2.34, 1.52, 4.49, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [6.34, 6.97, 7.92, 5.14, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [4.35, 6.15, 4.95, 3.81, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1.51, 1.21, 1.52, 1.91, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [1.9, 2.37, 2.57, 1.46, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [51.72, 40.28, 33.85, 33.56, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [24.75, 24.18, 17.93, 12.87, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [18.49, 29.3, 41.7, 49.8, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]]
   ]];


```````````````````````
Part 1 : Configuration
```````````````````````

- ``CHORDinnerRadius``
      default 108, inner radius of CHORD
      
- ``CHORDouterRadius``
   default 110, outer radius of CHORD

- ``CHORDFillOpacity``
      default 0.67, fill opacity of CHORD
      
- ``CHORDFillStrokeWidth``
   default "0.5px", stroke width of fill CHORD

- ``CHORDPadding``
      default 0.01, padding of CHORD

- ``CHORDAutoFillColor``
      default true, [true/false], whether auto assign color for each chord or not
      
- ``CHORDFillColor``
   default ["red"], a list, if not auto assign color, this list will be the color of chord
   
- ``CHORDFillStrokeColor``
   default ["black"], a list, if not auto assign color, this list will be the stroke color of chord

- ``CHORDouterARC``
      default true, [true/false], whether display outer arc or not
      
- ``CHORDouterARCAutoColor``
   default true, [true/false], whether auto assign color for outer arc or not
   
- ``CHORDouterARCColor``
   default ["red"], a list, if not auto assign color, this list will be the color of outer arc
   
- ``CHORDouterARCStrokeColor``
   default ["black"], a list, if not auto assign color, this list will be the stroke color of outer arc
   
- ``CHORDouterARCText``
   default true, [true/false], whether display text or not

**Example**: change data configuration of CHORD module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

               CHORDinnerRadius: 237,
               CHORDouterRadius: 238,
               CHORDFillOpacity:0.67,

     - .. code-block:: javascript

               CHORDinnerRadius: 180,
               CHORDouterRadius: 200,
               CHORDFillOpacity: 1,

   * - Image change

     - .. image:: _images/API_data_configuration_CHORD01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_CHORD01_before.html
     
     - .. image:: _images/API_data_configuration_CHORD01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_CHORD01_after.html

``````````````
Part 2 : Data
``````````````

- ``matrix``
   a matrix to display CHORD, first row is a list of column name, the others are weight between each chord
   
---------------------
6.15 REDIRECT module
---------------------

.. code-block:: javascript

	NGCircos01 = new NGCircos(NGCircosGenome,{
         SNPxlink: false,
         GENExlink: false,
         LOLLIPOPxlink: false,
         HISTOGRAMxlink: false,
         ARCxlink: false,
         CNVxlink: false,
         SCATTERxlink: false,
         BUBBLExlink: false,
	  });

.. note:: In each module which open the REDIRECT module, a parameter called **link** in the data must be contained, which is the address for the element.

```````````````````````
Part 1 : Configuration
```````````````````````

- ``SNPxlink``
   default false, [true/false], add/not xlink for SNP module

- ``GENExlink``
   default false, [true/false], add/not xlink for GENE module
         
- ``LOLLIPOPxlink``
   default false, [true/false], add/not xlink for LOLLIPOP module
            
- ``HISTOGRAMxlink``
   default false, [true/false], add/not xlink for HISTOGRAM module
               
- ``ARCxlink``
   default false, [true/false], add/not xlink for ARC module
                  
- ``CNVxlink``
   default false, [true/false], add/not xlink for CNV module
                     
- ``SCATTERxlink``
   default false, [true/false], add/not xlink for SCATTER module
   
- ``BUBBLExlink``
   default false, [true/false], add/not xlink for BUBBLE module
   
**Example**: change data configuration of REDIRECT module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

               LOLLIPOPxlink: true,
               ARCxlink: false,

     - .. code-block:: javascript

               LOLLIPOPxlink: false,
               ARCxlink: true,

   * - Image change

     - .. image:: _images/API_data_configuration_REDIRECT01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_REDIRECT01_before.html
     
     - .. image:: _images/API_data_configuration_REDIRECT01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_REDIRECT01_after.html

``````````````
Part 2 : Data
``````````````

- ``SNP``
   {chr: "8", pos: "19986711", value: "149", des: "rs12678919", color: "#991ECC",link:"https://www.ncbi.nlm.nih.gov/snp/rs12678919"}
   
- ``GENE``
   {chr: "EGFR", strand: "+", start: "57", end: "167", type:"cds", name:"EGFR",link:"https://www.intogen.org/search?gene=EGFR"}

- ``LOLLIPOP``
   {protein:"EGFR",chr:"7",pos:"101219410",strand:"+",CancerTypeNumber:"2",AA_pos:"AA_858",AA_change:"L/R",Consequence:"missense_variant",color:"#FEFF00",type:"Hetero",link:"https://www.intogen.org/search?gene=EGFR"}

- ``HISTOGRAM``
   {chr: "2L", start: "1", end: "1011544", name: "test histogram", value: "0.8",link:"https://www.ncbi.nlm.nih.gov"}
   
- ``ARC``
   {chr:"EGFR",start:"185",end:"338",color:"#FF7F0E",des:"Furin-like_domain",link:"https://www.intogen.org/search?gene=EGFR"}
   
- ``CNV``
   {chr: "1", start: "764788", end: "87109267", value: "2.5",link:"https://www.ncbi.nlm.nih.gov"}
   
- ``SCATTER``
   {chr: "1", start: "1102484", end: "1102578", name: "hsa-mir-200b", des: "breast cancer",link:"https://www.ncbi.nlm.nih.gov"}

- ``BUBBLE``
   {chr: "chr6", start: "1", end: "100", name: "TP53", value: "0.1", color: "red", layer: "3",link:"https://www.ncbi.nlm.nih.gov"}
   
add a link element as the hyper link address for each supported module.

---------------------
6.16 DOWNLOAD module
---------------------

For .png DOWNLOAD module, we need first to create a button with the code following.

.. code-block:: html

   <div class="svg-box img-container">
      <button class="svg-action-btn download-img">Download png ↓</button>
   </div>  
   
Add the code block below after the </script> tag of main picture and before the </body> tag:

.. code-block:: html

      <script src=../lib/saveSvgAsPng.js></script>
      <script>
                  
         (function(){
            var downloadImg = getEle(".download-img"),
               imgName = getEle("."+NGCircos1.svgClassName);
            downloadImg.addEventListener("click",function(){
               var mySvg = getEle("."+NGCircos1.svgClassName),
                  oImgName = imgName.value || NGCircos1.svgClassName;
               saveSvgAsPng(mySvg, oImgName+".png");

            })

            function getEle(obj){
               var d = document;
               return d.querySelector(obj);
            }
         })()

      </script>


For .svg DOWNLOAD module, we need first to create a button with the code following.

.. code-block:: html

   <a href="javascript:(function () { var e = document.createElement('script');if (window.location.protocol === 'https:') { e.setAttribute('src', '../lib/svg-crowbar.js'); } else { e.setAttribute('src', '../lib/svg-crowbar.js'); } e.setAttribute('class', 'svg-crowbar'); document.body.appendChild(e); })();" class="DownButtonNormal" >Download svg ↓</a>

```````````````````````
Part 1 : Configuration
```````````````````````

**Example**: change data configuration of DOWNLOAD module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: html

            <div class="svg-box img-container">
               <button class="svg-action-btn download-img">Download png ↓</button>
            </div>  
            <script src=../lib/saveSvgAsPng.js></script>
            <script>
                        
               (function(){
                  var downloadImg = getEle(".download-img"),
                     imgName = getEle("."+NGCircos1.svgClassName);
                  downloadImg.addEventListener("click",function(){
                     var mySvg = getEle("."+NGCircos1.svgClassName),
                        oImgName = imgName.value || NGCircos1.svgClassName;
                  
                     saveSvgAsPng(mySvg, oImgName+".png");

                  })

                  function getEle(obj){
                     var d = document;
                     return d.querySelector(obj);
                  }
               })()
            </script>

     - .. code-block:: html

            <a href="javascript:(function () { var e = document.createElement('script');if (window.location.protocol === 'https:') { e.setAttribute('src', '../lib/svg-crowbar.js'); } else { e.setAttribute('src', '../lib/svg-crowbar.js'); } e.setAttribute('class', 'svg-crowbar'); document.body.appendChild(e); })();" class="DownButtonNormal" >Download svg ↓</a>

   * - Image change

     - .. image:: _images/API_data_configuration_DOWNLOAD01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_DOWNLOAD01_before.html
     
     - .. image:: _images/API_data_configuration_DOWNLOAD01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_DOWNLOAD01_after.html

--------------------------
6.17 AUXILIARYLINE module
--------------------------

.. code-block:: javascript

	var AUXILIARYLINE01 = [ "AUXILIARYLINE01" , {
       startX: -100,
       startY: 0,
       endX: 100,
       endY: 0,
       AUXILIARYLINEType:"curve",
       AUXILIARYLINEControlPointX:0,
       AUXILIARYLINEControlPointY:-100,
       AUXILIARYLINELineType:"dot",
       AUXILIARYLINEDashArray:4,
       AUXILIARYLINEColor: "black",
       AUXILIARYLINEWidth: 2,
       AUXILIARYLINEMarker:true,
       AUXILIARYLINEMarkerType:"arrow",
       AUXILIARYLINEMarkerColor:"black",
       AUXILIARYLINEMarkerHeight:5,
       AUXILIARYLINEMarkerWidth:5,
       AUXILIARYLINEMarkerPosition:2,
       AUXILIARYLINEAnimationDispaly:false,
       AUXILIARYLINEAnimationDelay:50,
       AUXILIARYLINEAnimationTime:1000,
       AUXILIARYLINEAnimationType:"linear",
   }];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``startX``
      default 20, the X axis of start position
      
- ``startY``
   default 20, the Y axis of start position
   
- ``endX``
      default 20, the X axis of end position
      
- ``startY``
   default 20, the Y axis of end position

- ``AUXILIARYLINEType``
      default "straight", [straight/curve/broken], the line type
      
- ``AUXILIARYLINELineType``
   default "solid", [solid/dot], the line type

- ``AUXILIARYLINEControlPointX``
      default 0, X axis of control point if line type is curve or broken
      
- ``AUXILIARYLINEControlPointY``
   default 0, Y axis of control point if line type is curve or broken

- ``AUXILIARYLINEDashArray``
      default 3, dash array of line

- ``AUXILIARYLINEMarker``
      default false, [false/true] ,display marker or not
      
- ``AUXILIARYLINEMarkerType``
   default "circle", [circle/square/arrow/stub], type of marker
   
- ``AUXILIARYLINEMarkerColor``
   default "blue", color of marker
   
- ``AUXILIARYLINEMarkerHeight``
   default 5, height of marker
   
- ``AUXILIARYLINEMarkerWidth``
   default 5, width of marker
   
- ``AUXILIARYLINEMarkerPosition``
   default 2, [1/2/3], 1 means only start, 2 means only end, 3 means both start and end

**Example**: change data configuration of AUXILIARYLINE module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

                AUXILIARYLINEType:"curve",
                AUXILIARYLINEControlPointX:0,
                AUXILIARYLINEControlPointY:-100,
                AUXILIARYLINELineType:"dot",

     - .. code-block:: javascript

                AUXILIARYLINEType:"broken",
                AUXILIARYLINEControlPointX:0,
                AUXILIARYLINEControlPointY:100,
                AUXILIARYLINELineType:"solid",

   * - Image change

     - .. image:: _images/API_data_configuration_AUXILIARYLINE01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_AUXILIARYLINE01_before.html
     
     - .. image:: _images/API_data_configuration_AUXILIARYLINE01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_AUXILIARYLINE01_after.html      

- ``AUXILIARYLINEAnimationDisplay``
      default "false", [true/false], open/not open animation event of AUXILIARYLINE module.

- ``AUXILIARYLINEAnimationTime``
      default 1000, specifies the animation time in milliseconds.

- ``AUXILIARYLINEAnimationDelay``
      default 50, specifies the animation delay in milliseconds. 

- ``AUXILIARYLINEAnimationType``
      default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

-------------------
6.18 LEGEND module
-------------------

.. code-block:: javascript

	var LEGEND01 = [ "LEGEND01" , {
   x: -50,
   y: -230,
   title: " ",
   titleSize: 16,
   titleWeight: "bold",
   GapBetweenGraphicText:5,
   GapBetweenLines:20
   } , [
      {type: "circle", color:"#1E77B4",opacity:"1.0",circleSize:"8",text: "C.CK", textSize: "14",textWeight:"normal"},
      {type: "circle", color:"#AEC7E8",opacity:"1.0",circleSize:"8",text: "C.NPK", textSize: "14",textWeight:"normal"},
      {type: "circle", color:"#FF7F0B",opacity:"1.0",circleSize:"8",text: "GC.CK", textSize: "14",textWeight:"normal"},
      ......
      {type: "circle", color:"#DADB8D",opacity:"1.0",circleSize:"8",text: "Ascomycota", textSize: "14",textWeight:"normal"},
      {type: "circle", color:"#19BDCF",opacity:"1.0",circleSize:"8",text: "Basidiomycota", textSize: "14",textWeight:"normal"},
      {type: "circle", color:"#9ED9E5",opacity:"1.0",circleSize:"8",text: "Zygomycota", textSize: "14",textWeight:"normal"},
   ]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``x``
      default 20, the X axis of start position
      
- ``y``
   default 20, the Y axis of start position
   
- ``title``
      default "legend", the title of LEGEND
      
- ``titleSize``
   default 6, the size of title

- ``titleWeight``
      default "normal", [normal/bold/bolder/lighter/100/200/...], weight of title
      
- ``GapBetweenGraphicText``
   default 5, the gap between graphic and text

- ``GapBetweenLines``
      default 15, the gap between two legend lines
      
**Example**: change data configuration of LEGEND module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

               x: -50,
               y: -230,

     - .. code-block:: javascript

               x: 250,
               y: -230,

   * - Image change

     - .. image:: _images/API_data_configuration_LEGEND01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_LEGEND01_before.html
     
     - .. image:: _images/API_data_configuration_LEGEND01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_LEGEND01_after.html
 
--------------------
6.19 COMPARE module
--------------------

.. code-block:: javascript

	NGCircos01 = new NGCircos(NGCircosGenome,{
         compareEvent:true,
         compareEventGroupGapRate:0.1,
         compareEventGroupDistance:0,
	  });

```````````````````````
Part 1 : Configuration
```````````````````````

- ``compareEvent``
   default false, [true/false], open/not COMPARE module

- ``compareEventGroupGapRate``
   default 0.1, control the two-side gap rate on each group of genome
         
- ``compareEventGroupDistance``
   default 0, distance between two groups of genome
   
**Example**: change data configuration of COMPARE module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

               compareEventGroupGapRate:0.2,
               compareEventGroupDistance:100,

     - .. code-block:: javascript

               compareEventGroupGapRate:0.4,
               compareEventGroupDistance:300,

   * - Image change

     - .. image:: _images/API_data_configuration_COMPARE01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_COMPARE01_before.html
     
     - .. image:: _images/API_data_configuration_COMPARE01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_COMPARE01_after.html

``````````````
Part 2 : Data
``````````````

- ``SNP``
   compareGroup:1, [1/2], default 1, genome group number belong to

- ``CNV``
   compareGroup:1, [1/2], default 1, genome group number belong to

- ``HEATMAP``
   compareGroup:1, [1/2], default 1, genome group number belong to
   
- ``GENE``
   compareGroup:1, [1/2], default 1, genome group number belong to
   
- ``LINK``
   compareGroup:1, [1/2], default 1, genome group number belong to
   
- ``HISTOGRAM``
   compareGroup:1, [1/2], default 1, genome group number belong to
   
- ``LINE``
   compareGroup:1, [1/2], default 1, genome group number belong to
   
- ``WIG``
   compareGroup:1, [1/2], default 1, genome group number belong to
   
- ``SCATTER``
   compareGroup:1, [1/2], default 1, genome group number belong to
   
- ``ARC``
   compareGroup:1, [1/2], default 1, genome group number belong to
   
- ``LOLLIPOP``
   compareGroup:1, [1/2], default 1, genome group number belong to
   
- ``BACKGROUND``
   compareGroup:1, [1/2], default 1, genome group number belong to
              
------------------------
6.20 COMBINATION module
------------------------

.. code-block:: javascript

	NGCircos01 = new NGCircos(NGCircosGenome,{
         SNPMouseCombinationEvent:true,
         SNPMouseCombinationImageDisplay:true,
         SNPMouseCombinationImageTitle:"This is image",
         SNPMouseCombinationImageTitleSize:5,
         SNPMouseCombinationImageTitleWeight:"bold",
         SNPMouseCombinationImageTitleColor:"black",
         SNPMouseCombinationImagePositionX:0,
         SNPMouseCombinationImagePositionY:0,
         SNPMouseCombinationImageHeight:200,
         SNPMouseCombinationImageWidth:300,
         SNPMouseCombinationGraphDisplay:true,
         SNPMouseCombinationGraphTitle:"This is graph",
         SNPMouseCombinationGraphTitleSize:5,
         SNPMouseCombinationGraphTitleWeight:"bold",
         SNPMouseCombinationGraphTitleColor:"black",
         SNPMouseCombinationGraphType:"histogram",   //histogram, pie, line
         SNPMouseCombinationGraphPositionX:0,
         SNPMouseCombinationGraphPositionY:0,
         SNPMouseCombinationGraphHeight:200,
         SNPMouseCombinationGraphWidth:300,
         SNPMouseCombinationGraphHistogramBarColor:"blue",
         SNPMouseCombinationGraphHistogramPadding:30,
         SNPMouseCombinationGraphHistogramPositionCorrectX:0,
         SNPMouseCombinationGraphPieAutoColor:true,
         SNPMouseCombinationGraphPieColor:["black","blue","orange","red","green"],
         SNPMouseCombinationGraphPieSize:50,
         SNPMouseCombinationGraphPieStroke:true,
         SNPMouseCombinationGraphPieStrokeColor:"black",
         SNPMouseCombinationGraphPieStrokeWidth:1,
         SNPMouseCombinationGraphPieOpacity:1.0,
         SNPMouseCombinationGraphLineType:"linear",
         SNPMouseCombinationGraphLineColor:"black",
         SNPMouseCombinationGraphLineWidth:1,
         SNPMouseCombinationGraphLinePoint:false,
         SNPMouseCombinationGraphLinePointSize:5,
         SNPMouseCombinationGraphLinePointAutoColor:true,
         SNPMouseCombinationGraphLinePointColor:["black","blue","orange","red","green"],
         SNPMouseCombinationGraphLinePointStroke:true,
         SNPMouseCombinationGraphLinePointStrokeColor:"black",
         SNPMouseCombinationGraphLinePointStrokeWidth:1,
         SNPMouseCombinationGraphLinePointOpacity:1,
         SNPMouseCombinationGraphLinePositionCorrectX:0,
         SNPMouseCombinationTextDisplay:true,
         SNPMouseCombinationTextColor:"red",
         SNPMouseCombinationTextSize:3,
         SNPMouseCombinationTextWeight:"bold",
         SNPMouseCombinationTextPositionCorrectX:0,
         SNPMouseCombinationTextPositionCorrectY:0,
	  });

```````````````````````
Part 1 : Configuration
```````````````````````

- ``SNPMouseCombinationEvent``
   default false, [true/false], open/not COMBINATION module for SNP module

- ``SNPMouseCombinationImageDisplay``
   default false, [true/false], open/not image display in COMBINATION module for SNP module

- ``SNPMouseCombinationImageTitle``
   default "This is image", title of the image

- ``SNPMouseCombinationImageTitleSize``
   default 5, size of the title

- ``SNPMouseCombinationImageTitleWeight``
   default "bold", weight of title

- ``SNPMouseCombinationImageTitleColor``
   default "black", color of title
         
- ``SNPMouseCombinationImagePositionX``
   default 0, the X axis position of image

- ``SNPMouseCombinationImagePositionY``
   default 0, the Y axis position of image

- ``SNPMouseCombinationImageHeight``
   default 200, the height of image
   
- ``SNPMouseCombinationImageWidth``
   default 300, the Width of image

- ``SNPMouseCombinationGraphDisplay``
   default false, [true/false], open/not graph display in COMBINATION module for SNP module
   
- ``SNPMouseCombinationGraphTitle``
   default "This is graph", title of the graph
   
- ``SNPMouseCombinationGraphTitleSize``
   default 5, size of the title   

- ``SNPMouseCombinationGraphTitleWeight``
   default "bold", weight of title

- ``SNPMouseCombinationGraphTitleColor``
   default "black", color of title
   
- ``SNPMouseCombinationGraphType``
   default "histogram", [histogram/pie/line], type of graph

- ``SNPMouseCombinationGraphPositionX``
   default 0, the X axis position of graph

- ``SNPMouseCombinationGraphPositionY``
   default 0, the Y axis position of graph

- ``SNPMouseCombinationGraphHeight``
   default 200, the height of graph
   
- ``SNPMouseCombinationGraphWidth``
   default 300, the Width of graph
   
- ``SNPMouseCombinationGraphHistogramBarColor``
   default "blue", the bar color of histogram graph
      
- ``SNPMouseCombinationGraphHistogramPadding``
   default 30, the padding between bar of histogram graph
      
- ``SNPMouseCombinationGraphHistogramPositionCorrectX``
   default 0, the correction distance of X axis in histogram
         
- ``SNPMouseCombinationGraphPieAutoColor``
   default true, [true/false], whether use auto color for pie graph or not
         
- ``SNPMouseCombinationGraphPieColor``
   default ["black","blue","orange","red","green"], the color for pie graph if auto color is false
            
- ``SNPMouseCombinationGraphPieSize``
   default 50, the size of pie graph
   
- ``SNPMouseCombinationGraphPieStroke``
   default true, [true/false], whether each pie has a stroke or not
            
- ``SNPMouseCombinationGraphPieStrokeColor``
   default "black", the color of stroke in pie
      
- ``SNPMouseCombinationGraphPieStrokeWidth``
   default 1, the width of stroke in pie
            
- ``SNPMouseCombinationGraphPieOpacity``
   default 1.0, the opacity of pie
         
- ``SNPMouseCombinationGraphLineType``
   default "linear", the line type for line graph
            
- ``SNPMouseCombinationGraphLineColor``
   default "black", the color of line in line graph
            
- ``SNPMouseCombinationGraphLineWidth``
   default 1, the width of line in line graph      
                     
- ``SNPMouseCombinationGraphLinePoint``
   default false, [true/false], whether display the broken point in line graph

- ``SNPMouseCombinationGraphLinePointSize``
   default 5, the size of broken point      
                     
- ``SNPMouseCombinationGraphLinePointAutoColor``
   default true, [true/false], whether display the broken point in auto color
      
- ``SNPMouseCombinationGraphLinePointColor``
   default ["black","blue","orange","red","green"], the color for broken point if auto color is false     
                     
- ``SNPMouseCombinationGraphLinePointStroke``
   default true, [true/false], whether display the broken point stroke
         
- ``SNPMouseCombinationGraphLinePointStrokeColor``
   default "black", the stroke color for broken point     
                     
- ``SNPMouseCombinationGraphLinePointStrokeWidth``
   default 1, the stroke width for broken point
            
- ``SNPMouseCombinationGraphLinePointOpacity``
   default 1, the opacity for broken point     
                     
- ``SNPMouseCombinationGraphLinePositionCorrectX``
   default 0, the correction distance of X axis for line 

- ``SNPMouseCombinationTextDisplay``
   default false, [true/false], whether display the text
         
- ``SNPMouseCombinationTextColor``
   default "red", the color for text   
                     
- ``SNPMouseCombinationTextSize``
   default 3, the size of text
            
- ``SNPMouseCombinationTextWeight``
   default "bold", the weight of text     
                     
- ``SNPMouseCombinationGraphLinePositionCorrectX``
   default 0, the correction distance of X axis for text 

- ``SNPMouseCombinationGraphLinePositionCorrectY``
   default 0, the correction distance of Y axis for text
   
**Example**: change data configuration of COMBINATION module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

               SNPMouseCombinationGraphType:"histogram"

     - .. code-block:: javascript

               SNPMouseCombinationGraphType:"pie"

   * - Image change

     - .. image:: _images/API_data_configuration_COMBINATION01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_COMBINATION01_before.html
     
     - .. image:: _images/API_data_configuration_COMBINATION01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_COMBINATION01_after.html

``````````````
Part 2 : Data
``````````````

- ``SNP``

   {chr: "10", pos: "121577821", value: "169.699", des: "rs2981579", color: "rgb(153,102,0)", index: "1", image: "https://raw.githubusercontent.com/mrcuizhe/Image_NGCircos/master/combination_snp/EUR.rs2981579.400kb-1.png"}

   Index is the row number of this snp in the matrix, image is the url address of the image in COMBINATION
   
- ``matrix``

   [
    ['eas', 'sas', 'afr', 'eur', 'amr'],
    ['0.551', '0.61', '0.339', '0.549', '0.57'], 
    ............,
    ['0.999', '0.97', '0.688', '0.912', '0.94'], 
    ['0.12', '0.08', '0.116', '0.13', '0.06'],
   ]

   First row of this matrix store the column name of graph, users can freely change the column number or name
   
-------------------
6.21 BUBBLE module
-------------------

.. code-block:: javascript

	var BUBBLE01 = [ "BUBBLE01" , {
      minRadius: 100,
      maxRadius: 105,
      blockStroke:true,
      blockStrokeColor:"black",
      blockStrokeWidth:1,
      blockFill:false,
      blockFillColor:"white",
      bubbleMaxSize:5,
      bubbleMinSize:2,
      maxColor: "red",
      minColor: "green",
      totalLayer:3,
      ValueAxisManualScale:false,
      ValueAxisMaxScale:10,
      ValueAxisMinScale:0,
      BUBBLEAnimationDisplay: false,
      BUBBLEAnimationTime: 2000,
      BUBBLEAnimationDelay: 20,
      BUBBLEAnimationType: "bounce",
   } , [
      {chr: "chr6", start: "1", end: "100", name: "TP53", value: "0.1", color: "red", layer: "3",html:" "},
      {chr: "chr6", start: "100", end: "200", name: "TP53", value: "0.4", color: "blue", layer: "3"},
      {chr: "chr6", start: "200", end: "300", name: "TP53", value: "0.8", color: "green", layer: "3"},
      {chr: "chr6", start: "300", end: "400", name: "TP53", value: "0.9", color: "red", layer: "3"},
      ......
      {chr: "chr6", start: "600", end: "700", name: "TP53", value: "0.8", color: "red", layer: "1"},
      {chr: "chr6", start: "700", end: "800", name: "TP53", value: "0.2", color: "blue", layer: "1"},
      {chr: "chr6", start: "800", end: "900", name: "TP53", value: "0.6", color: "green", layer: "1"},
      {chr: "chr6", start: "900", end: "1000", name: "TP53", value: "0.5", color: "green", layer: "1"},
   ]];

```````````````````````
Part 1 : Configuration
```````````````````````

- ``minRadius``
      default 20, inner radius of BUBBLE

- ``maxRadius``
      default 80, outer radius of BUBBLE

- ``blockStroke``
      default true, [true/false], whether to show stroke for block or not

- ``blockStrokeColor``
      default "black", color of block stroke
   
- ``blockStrokeWidth``
      default 1, width of block stroke
   
- ``blockFill``
      default true, [true/false], whether to fill the block or not
      
- ``blockFillColor``
      default "white", color for block
            
- ``bubbleMaxSize``
      default 5, maximum size for bubble
              
- ``bubbleMinSize``
      default 2, minimum size for bubble
              
- ``maxColor``
      default "red", color for the bubble whose value is highest
              
- ``minColor``
      default "green", color for the bubble whose value is lowest
              
- ``totalLayer``
      default 3, totle layers for the BUBBLE module
      
- ``ValueAxisManualScale``
   default "false", [false/true], whether manually control the scale of value

- ``ValueAxisMaxScale``
   default "10", the maxmium value manually set for value
   
- ``ValueAxisMaxScale``
   default "0", the minimum value manually set for value
              
**Example**: change data configuration of BUBBLE module

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

               minRadius: 20,
               maxRadius: 80,
               maxColor: "yellow",
               minColor: "black",

     - .. code-block:: javascript

               minRadius: 120,
               maxRadius: 180,
               maxColor: "red",
               minColor: "green",

   * - Image change

     - .. image:: _images/API_data_configuration_BUBBLE01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_BUBBLE01_before.html
     
     - .. image:: _images/API_data_configuration_BUBBLE01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/API_data_configuration_BUBBLE01_after.html
               
- ``BUBBLEAnimationDisplay``
      default "false", [true/false], open/not open animation event of BUBBLE module

- ``BUBBLEAnimationTime``
      default 2000, specifies the animation time in milliseconds.

- ``BUBBLEAnimationDelay``
      default 20, specifies the animation delay in milliseconds. 

- ``BUBBLEAnimationType``
      default "bounce", [linear/circle/elastic/bounce], "linear" means ordinary linear change; "circle" means change to the final state of the animation; "elastic" means change to the final state with a bounce; "bounce" means bounce a few times in the final state.

**Example**: BUBBLE Animation

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

      - Before
      - After

   * - Code change

      - .. code-block:: javascript

               BUBBLEAnimationDisplay:true,
               BUBBLEAnimationDelay:50,
               BUBBLEAnimationType:"linear",

      - .. code-block:: javascript

               BUBBLEAnimationDisplay:true,
               BUBBLEAnimationDelay:50,
               BUBBLEAnimationType:"bounce",

   * - Image change

      - .. image:: _images/BUBBLEAnimation01_before.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/BUBBLEAnimation01_before.html
     
      - .. image:: _images/BUBBLEAnimation01_after.png
               :scale: 50%
               :height: 600px
               :width: 600px
               :alt: alternate text
               :align: left
               :target: pages/BUBBLEAnimation01_after.html

``````````````
Part 2 : Data
``````````````

- The 1 column(``chr``) is the name of the chromosome.
- The 2 column(``start``) is the start of the region.
- The 3 column(``end``) is the end of the region.
- The 4 column(``name``) is the name of the bubble.
- The 5 column(``value``) is the value of the bubble.
- The 6 column(``color``) is the specific color of the bubble.
- The 7 column(``layer``) is the specific layer of the bubble.
- The 8 column(``html``) is the html for tooltips.

=============================
7. API: Genome configuration
=============================
**"Genome configuration"** defines the number and size of chromosomes.

.. note:: **"Genome configuration"** is especially simple compared to the other two modules. But it is very important for beginners, so here is a special emphasis on how to use it.

-------------------------
7.1 Genome configuration
-------------------------

Genome configuration is set in a **<script>** tag. Here we configure a genome with **1,2,3,X,Y chromosome**.

.. code-block:: javascript

	  var NGCircosGenome = [       // Configure your own genome here.
      [
	     ["1" , 247249719],
	     ["2" , 242951149],
	     ["3" , 199501827],
	     ["X" , 154913754],
	     ["Y" , 57772954]
      ]
	  ];

**Example**: add chromosome

.. list-table::
   :widths: 10 60 60
   :header-rows: 1

   * - Example

     - Before
     - After

   * - Code change

     - .. code-block:: javascript

   	  var NGCircosGenome = [
         [
   	     ["1" , 247249719],
   	     ["2" , 242951149],
   	     ["3" , 199501827],
   	     ["X" , 154913754],
   	     ["Y" , 57772954]
         ]
   	  ];

     - .. code-block:: javascript

   	  var NGCircosGenome = [
         [
   	     ["1" , 247249719],
   	     ["2" , 242951149],
   	     ["3" , 199501827],
               ["4" , 191154276],
               ["5" , 180915260],
               ["6" , 171115067],
               ["7" , 159138663],
   	     ["X" , 154913754],
   	     ["Y" , 57772954]
         ]
   	  ];

   * - Image change

     - .. image:: _images/API_genome_configuration01_before.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_genome_configuration01_before.html
     
     - .. image:: _images/API_genome_configuration01_after.png
          :scale: 50%
          :height: 600px
          :width: 600px
          :alt: alternate text
          :align: left
          :target: pages/API_genome_configuration01_after.html

---------------------------------------------------------
7.2 Example: Customize your genome by Main configuration
---------------------------------------------------------

.. code-block:: html

	<script>
	  var NGCircosGenome = [      // Configure your own genome here.
      [
	     ["1" , 247249719],
	     ["2" , 242951149],
	     ["3" , 199501827],
	     ["X" , 154913754],
	     ["Y" , 57772954]
      ]
	  ];
	  NGCircos01 = new NGCircos(NGCircosGenome,{       // Initialize NG-Circos with "NGCircosGenome" and Main configuration
	     target : "example",                              // Main configuration "target"
	     svgWidth : 900,                                  // Main configuration "svgWidth"
	     svgHeight : 600,                                 // Main configuration "svgHeight"
	     innerRadius: 246,                                // Main configuration "innerRadius"
	     outerRadius: 250,                                // Main configuration "outerRadius"
	     genomeFillColor: ["#999999"]                     // Main configuration "genomeFillColor"
	  });
	  NGCircos01.draw_genome(NGCircos01.genomeLength);  // NG-Circos callback
     NGCircos01.draw_genome(NGCircos01.genomeLength2); // NG-Circos callback second time
	</script>

.. image:: _images/demo_genome_configuration02.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/demo_genome_configuration02.html

---------------------------------
7.3 Example: Human genome (hg19)
---------------------------------

.. code-block:: html

      <script>
	var NGCircosGenome = [  //human hg19
      [
	     ["1" , 249250621],
	     ["2" , 243199373],
	     ["3" , 198022430],
	     ["4" , 191154276],
	     ["5" , 180915260],
	     ["6" , 171115067],
	     ["7" , 159138663],
	     ["8" , 146364022],
	     ["9" , 141213431],
	     ["10" , 135534747],
	     ["11" , 135006516],
	     ["12" , 133851895],
	     ["13" , 115169878],
	     ["14" , 107349540],
	     ["15" , 102531392],
	     ["16" , 90354753],
	     ["17" , 81195210],
	     ["18" , 78077248],
	     ["19" , 59128983],
	     ["20" , 63025520],
	     ["21" , 48129895],
	     ["22" , 51304566],
	     ["X" , 155270560],
	     ["Y" , 59373566]
      ]
	];
      </script>

.. image:: _images/demo_genome_configuration03.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/demo_genome_configuration03.html

-------------------------------------------------------
7.4 Example: Add chromosome band on Human genome(hg19)
-------------------------------------------------------

The chromosome band represents the approximate location of bands seen on Giemsa-stained chromosomes. Color of chromosome band is the as Circos.

.. list-table::
   :widths: 15 15 15 10 20
   :header-rows: 1

   * - Species
     - Genome version
     - Data name
     - Genome
     - cytoBand in UCSC
   * - Human
     - grch38
     - ARC_grch38
     - `genome <./genome_resource/karyotype.human.grch38_genome.js>`__
     - `karyotype.human.grch38.js <./genome_resource/karyotype.human.grch38.js>`__
   * - Human
     - hg19
     - ARC_hg19
     - `genome <./genome_resource/karyotype.human.hg19_genome.js>`__
     - `karyotype.human.hg19.js <./genome_resource/karyotype.human.hg19.js>`__
   * - human
     - hg18
     - ARC_hg18
     - `genome <./genome_resource/karyotype.human.hg18_genome.js>`__
     - `karyotype.human.hg18.js <./genome_resource/karyotype.human.hg18.js>`__
   * - Mouse
     - mm10
     - ARC_mm10
     - `genome <./genome_resource/karyotype.mouse.mm10_genome.js>`__
     - `karyotype.mouse.mm10.js <./genome_resource/karyotype.mouse.mm10.js>`__
   * - Mouse
     - mm9
     - ARC_mm9
     - `genome <./genome_resource/karyotype.mouse.mm9_genome.js>`__
     - `karyotype.mouse.mm9.js <./genome_resource/karyotype.mouse.mm9.js>`__

.. code-block:: html

      <script src="../data/karyotype.human.hg19.js"></script>
      <script>
	var NGCircosGenome = [  //human hg19
      [
	     ["1" , 249250621],
	     ["2" , 243199373],
	     ["3" , 198022430],
	     ["4" , 191154276],
	     ["5" , 180915260],
	     ["6" , 171115067],
	     ["7" , 159138663],
	     ["8" , 146364022],
	     ["9" , 141213431],
	     ["10" , 135534747],
	     ["11" , 135006516],
	     ["12" , 133851895],
	     ["13" , 115169878],
	     ["14" , 107349540],
	     ["15" , 102531392],
	     ["16" , 90354753],
	     ["17" , 81195210],
	     ["18" , 78077248],
	     ["19" , 59128983],
	     ["20" , 63025520],
	     ["21" , 48129895],
	     ["22" , 51304566],
	     ["X" , 155270560],
	     ["Y" , 59373566]
      ]
	];
      </script>

.. image:: _images/demo_genome_configuration04.png
   :scale: 50%
   :alt: alternate text
   :align: left
   :target: pages/demo_genome_configuration04.html

