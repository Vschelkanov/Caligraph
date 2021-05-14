# Caligraph
Caligraph analysis in clickhouse

Clickhouse allows to upload and perform analysis of 300 mln Caligraph triplets on ordinary computer.

Environment:
<ul>HW:
  <li>Intel(R) Core(TM) i5 CPU 750@2.67GHz
  <li>RAM 12 GB
 </ul>

<ul> SW:
<li>Windows 10
<li>WSL Ubuntu 20.04 LTS


<li>Clickhouse-server 21.4.5
<li>Python 3.7.2rcl
  </ul>


Steps:
<ul> 
  <li> Download and unzip <a href="http://caligraph.org/resources.html"> Caligraph data </a>
  <li> Install Clickhouse server locally - <a href="https://www.digitalocean.com/community/tutorial_collections/how-to-install-and-use-clickhouse">good guide</a>
  <li> <a href="https://github.com/Vschelkanov/Caligraph/blob/main/kg_create_table.ipynb">kg_create_table.ipynb:</a> Create table for Caligraph trpilets
  <li> <a href="https://github.com/Vschelkanov/Caligraph/blob/main/kg_upload_data.ipynb">kg_upload_data.ipynb:</a>> Upload data from Caligraph .nt files to Clickhouse table
    <li> <a href="https://github.com/Vschelkanov/Caligraph/blob/main/kg_explore_data.ipynb">kg_explore_data.ipynb:</a> Make a breif graph data exploration
  </ul>
