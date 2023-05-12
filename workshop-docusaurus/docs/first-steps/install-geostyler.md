
# Install GeoStyler

## Install GeoStyler UI

Since we are using npm, the installation of GeoStyler is straightforward.
Open a terminal and run the following command from the root of your application directory:

<pre>npm i geostyler@12.0.0</pre>

Additionally, we have to install a few dependencies, which can be installed in the same manner:

<pre>npm i ol@7 antd@4</pre>

Through this, we install [OpenLayers](https://openlayers.org/) in version 7 and [antd](https://ant.design/) in version 4. OpenLayers will be used
for the displaying of (preview-) maps and antd provides the very basic ui components, such as buttons.

# Install GeoStyler Parsers

The Style and Data Parsers have to be installed separately. This makes sure that you really just installed those parsers that you actually want to use.
In this workshop, we will use the SLD and OpenLayers Style Parser, as well as the WFS Data Parser.

Execute following command to install the parsers:

<pre>npm i geostyler-sld-parser@5.0.1</pre>
<pre>npm i geostyler-openlayers-parser@4.1.1</pre>
<pre>npm i geostyler-wfs-parser@2.0.0</pre>
