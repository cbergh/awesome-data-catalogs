


# Awesome Data Discovery and Observability

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

This repository contains a curated list of awesome data data catalogs and observability platforms that help you discover, manage, and observe data in your organization. 

<br>

## Contents: Existing Data Discovery and Observability Solutions

| [OSS](#opensource)       | [Proprietary](#proprietary)    | 
|--------------------------|--------------------------------| 
| [📙 Amundsen](#amundsen) | [📕 Collibra](#collibra)       | 
| [📙 DataHub](#datahub)   | [📕 Informatica](#informatica) | 
| [📙 Marquez](#marquez)   | [📕 Alation](#alation)         |                          
| [📙 Atlas](#atlas)       | [📕 Atlan](#atlan)             |                          
| [📙 CKAN](#ckan)         | [📕Stemma](#stemma)            |                         
| [📙 Magda](#magda)       | [📒 Google DC](#google)        |
|                           | [📒 Azure DC](#azure)         |                         
|                           | [🔍 Monte Carlo](#montecarlo) |
|                           | [🔍 Databand](#databand)      |
|                           | [🔍 Datafold](#datafold)      |
|                           | [🔍 Ataccama](#ataccama)      | 
<br>

<a name="opensource"></a>
## 📙 Open-Source Data Catalogs

<a name="amundsen"></a>
### Amundsen 
[Website](https://www.amundsen.io/) | [GitHub](https://github.com/amundsen-io/amundsen)

A popular open-source data catalog for metadata management and data discovery originated from Lyft. 

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:----:|:---:|:---:|:--:|:---:|:--:|:---:|:--:| 
| ❌ | ✔️  | ✔️  | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ 

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push </li>
<li><b>UX personalization:</b> No</li> 
<li><b>AI autowiring:</b> No</li> 
<li><b>Rich data profiling:</b>  No</li> 
<li><b>Recommendations:</b> Yes </li>
<li><b>Schemas, Description:</b> Yes</li>
<li><b>Complex schemas:</b> No </li>
<li><b>Data preview:</b> Yes </li>
<li><b>Column statistics:</b> Yes </li>
<li><b>Data owner:</b> Yes</li>
<li><b>Top data users:</b> Yes </li>
<li><b>Change notifications:</b>No </li>
<li><b>Change feed:</b> No </li>
<li><b>Deployment:</b>  </li> 
<li><b>Supported data sources:</b> Hive, Redshift, Druid, RDBMS, Presto, Snowflake </li>
</ul>
</details>

<br>

<a name="datahub"></a>
### DataHub

DataHub is an open-source data catalog featuring data discovery, data governance, metadata management. 

[Website](https://datahubproject.io/) | [GitHub](https://github.com/linkedin/datahub)

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:----:|:---:|:---:|:--:|:---:|:--:|:---:|:--:| 
| ❌ | ✔️  | ✔️ | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push, Pull</li>
<li><b>UX personalization:</b> No</li> 
<li><b>AI autowiring:</b> No</li> 
<li><b>Rich data profiling:</b> No</li> 
<li><b>Recommendations:</b> ? </li>
<li><b>Schemas, Description:</b> Yes</li>
<li><b>Complex schemas:</b> No </li>
<li><b>Data preview:</b> ? </li>
<li><b>Column statistics:</b> No </li>
<li><b>Data owner:</b> Yes</li>
<li><b>Top data users:</b> ? </li>
<li><b>Change notifications:</b> No </li>
<li><b>Change feed:</b> No </li>
<li><b>Deployment:</b>  </li> 
<li><b>Supported data sources:</b> Hive, Kafka, RDBMS </li>
</ul>
</details>

<br>

<a name="marquez"></a>
### Marquez

[Website](https://marquezproject.github.io/marquez/) | [GitHub](https://github.com/MarquezProject/marquez)

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:-----------:|:--:|:--:|:--:|:---:|:--:|:---:|:--:|:---:| 
| OpenLineage | ✔️ | ❌| ✔️ | ? | ❌ | ❌ | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push </li>
<li><b>UX personalization:</b> No</li> 
<li><b>AI autowiring:</b> No</li> 
<li><b>Rich data profiling:</b> No</li>
<li><b>Recommendations:</b> No </li>
<li><b>Schemas, Description:</b> Yes</li>
<li><b>Complex schemas:</b> No </li>
<li><b>Data preview:</b> Yes </li>
<li><b>Column statistics:</b> No </li>
<li><b>Data owner:</b> Yes</li>
<li><b>Top data users:</b> ? </li>
<li><b>Change notifications:</b> No </li>
<li><b>Change feed:</b> No </li>
<li><b>Deployment:</b>  </li> 
<li><b>Supported data sources:</b> S3, Kafka </li>
</ul>
</details>

<br>

<a name="atlas"></a>
### Atlas 

[Website](https://atlas.apache.org/#/) | [GitHub](https://github.com/apache/atlas)

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:----:|:---:|:---:|:--:|:---:|:--:|:---:|:--:| 
| ❌ | ✔️  | ❌  | ✔️ | ❌ | ❌ | ❌ | ❌ | ❌|

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push </li>
<li><b>UX personalization:</b> No</li> 
<li><b>AI autowiring:</b> No</li> 
<li><b>Rich data profiling:</b> No</li>
<li><b>Recommendations:</b> No </li>
<li><b>Schemas, Description:</b> Yes</li>
<li><b>Complex schemas:</b> No </li>
<li><b>Data preview:</b> No </li>
<li><b>Column statistics:</b> No </li>
<li><b>Data owner:</b> No</li>
<li><b>Top data users:</b> ? </li>
<li><b>Change notifications:</b> Yes </li>
<li><b>Change feed:</b> No </li>
<li><b>Deployment:</b>  </li>  
<li><b>Supported data sources:</b>HBase, Hive, Sqoop, Kafka, Storm  </li>
</ul>
</details>

<br>

<a name="ckan"></a>
### CKAN

[Website](https://ckan.org/) | [GitHub](https://github.com/ckan/ckan)

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:---:|:--:|:---:|:--:| 
| ❌ | ✔️ | ❌  | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push </li>
<li><b>UX personalization:</b> No</li> 
<li><b>AI autowiring:</b> No</li> 
<li><b>Rich data profiling:</b> No</li>
<li><b>Recommendations:</b> ? </li>
<li><b>Schemas, Description:</b> ?</li>
<li><b>Complex schemas:</b> ? </li>
<li><b>Data preview:</b> ? </li>
<li><b>Column statistics:</b> ? </li>
<li><b>Data owner:</b> ?</li>
<li><b>Top data users:</b> ? </li>
<li><b>Change notifications:</b> ? </li>
<li><b>Change feed:</b> ? </li>
<li><b>Deployment:</b>  </li> 
<li><b>Supported data sources:</b>  </li>
</ul>
</details>

<br>

<a name="magda"></a>
### Magda

[Website](https://magda.io/) | [GitHub](https://github.com/magda-io/magda)

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:---:|:--:|:---:|:--:| 
| ❌ | ✔️ | ❌  | ❌ | ✔️ | ❌ | ❌ | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push via UI </li>
<li><b>UX personalization:</b> No</li> 
<li><b>AI autowiring:</b> No</li> 
<li><b>Rich data profiling:</b> No</li>
<li><b>Recommendations:</b> No </li>
<li><b>Schemas, Description:</b> Yes</li>
<li><b>Complex schemas:</b> No </li>
<li><b>Data preview:</b> Yes </li>
<li><b>Column statistics:</b> No </li>
<li><b>Data owner:</b> Yes</li>
<li><b>Top data users:</b> ? </li>
<li><b>Change notifications:</b> No </li>
<li><b>Change feed:</b> No </li>
<li><b>Deployment:</b>  </li> 
<li><b>Supported data sources:</b> Mostly geodata </li>
</ul>
</details>

<br>

<a name="proprietary"></a>
## 📕 Proprietary Data Catalogs

<a name="collibra"></a>
### Collibra

[Website](https://github.com/collibra) | [GitHub](https://www.collibra.com/)

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:--:|:---:|:--:|:---:|:-:|:--:|:--:| 
| ❌ | ✔️ | ?  | ✔️ | ❌ | ❌ | ? | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push </li>
<li><b>UX personalization:</b> Yes</li> 
<li><b>AI autowiring:</b> ?</li> 
<li><b>Network-based:</b> No</li> 
<li><b>Rich data profiling:</b> ?</li> 
<li><b>Supported data sources:</b>  </li>
</ul>
</details>

<br>

<a name="informatica"></a>
### Informatica

[Website](https://www.informatica.com/) | [GitHub](https://github.com/InformaticaCloudApplicationIntegration) 

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:--:|:--:|:---:|:--:| 
| ❌ | ✔️ | ✔️  | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push </li>
<li><b>UX personalization:</b> ?</li> 
<li><b>AI autowiring:</b> ?</li> 
<li><b>Network-based:</b> Yes</li> 
<li><b>Rich data profiling:</b> Yes</li> 
<li><b>Supported data sources:</b>  </li>
</ul>
</details>

 <br>

<a name="alation"></a>
### Alation

[Website](https://www.alation.com/) | [GitHub](https://github.com/Alation)

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:--:|:--:|:---:|:---:| 
| ❌ | ✔️ | ❌  | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push </li>
<li><b>UX personalization:</b> Yes</li> 
<li><b>AI autowiring:</b> No</li> 
<li><b>Network-based:</b> No</li> 
<li><b>Rich data profiling:</b> No</li> 
<li><b>Supported data sources:</b>  </li>
</ul>
</details>

<br>

<a name="atlan"></a>
### Atlan
[Website](https://atlan.com/) | [GitHub](https://github.com/atlanhq)

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:---:|:--:|:---:|:---:| 
| ❌ | ✔️ | ❌  | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Pull </li>
<li><b>UX personalization:</b> ?</li> 
<li><b>AI autowiring:</b> ?</li> 
<li><b>Network-based:</b> No</li> 
<li><b>Rich data profiling:</b> ?</li> 
<li><b>Supported data sources:</b> Presto, Deequ, Atlas, Airflow, Hudi  </li>
</ul>
</details>

<br>

<a name="stemma"></a>
### Stemma

[Website](https://www.stemma.ai/)  

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:---:|:--:|:--:|:--:| 
| ❌ | ✔️ | ✔️  | ✔️ | ❌ | ❌ | ? | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push </li>
<li><b>UX personalization:</b> No</li> 
<li><b>AI autowiring:</b> No</li> 
<li><b>Network-based:</b> No</li> 
<li><b>Rich data profiling:</b> No</li> 
<li><b>Supported data sources:</b>  </li>
</ul>
</details>

<br>

<a name="talend"></a>
### Talend

[Website](https://www.talend.com/) | [GitHub](https://github.com/Talend)

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:---:|:--:|:--:|:--:| 
| ❌ | ✔️ | ? | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push </li>
<li><b>UX personalization:</b> Yes</li> 
<li><b>AI autowiring:</b> ?</li> 
<li><b>Network-based:</b> ?</li> 
<li><b>Rich data profiling:</b> Yes</li> 
<li><b>Supported data sources:</b>  </li>
</ul>
</details>

<br>

<a name="monocloud"></a>
## 📒 Monocloud Data Catalogs

<a name="talend"></a>
### Google Cloud Data Catalog

[Website](https://cloud.google.com/data-catalog) | [GitHub](https://github.com/GoogleCloudPlatform)

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:---:|:--:|:--:|:--:| 
| ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ? | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Pull </li>
<li><b>UX personalization:</b> ?</li> 
<li><b>AI autowiring:</b> ?</li> 
<li><b>Network-based:</b> No</li> 
<li><b>Rich data profiling:</b> No</li> 
<li><b>Supported data sources:</b>  </li>
</ul>
</details>

<br>

<a name="talend"></a>
### Azure Data Catalog

[Website](https://azure.microsoft.com/en-us/services/data-catalog/)  

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:---:|:--:|:--:|:--:| 
| ❌ | ✔️ | ? | ✔️ | ❌ | ❌ | ? | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Pull </li>
<li><b>UX personalization:</b> ?</li> 
<li><b>AI autowiring:</b> ?</li> 
<li><b>Network-based:</b> ?</li> 
<li><b>Rich data profiling:</b> ?</li> 
<li><b>Supported data sources:</b>  </li>
</ul>
</details>

<br>

<a name="observability"></a>
## 🔍 Data Observability Platforms

<a name="montecarlo"></a>
### Monte Carlo

[Website](https://www.montecarlodata.com/)  

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:---:|:--:|:--:|:--:| 
| ❌ | ✔️ | ❌ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ✔️ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Pull </li>
<li><b>UX personalization:</b> ?</li> 
<li><b>AI autowiring:</b> ?</li> 
<li><b>Network-based:</b> ?</li> 
<li><b>Rich data profiling:</b> ?</li> 
<li><b>Supported data sources:</b> Snowflake, Hive, Kafka, Looker, Redshift, Tableau, Big Query, Airflow, Fivetran, Presto, Mode, Periscope, Databricks, Glue, dbt, Chartio, Spark, AWS, S3, data.world, Google Cloud Platform </li>
</ul>
</details>

<br>

<a name="databand"></a>
### Databand

[Website](https://databand.ai/) | [GitHub](https://github.com/databand-ai/)

Databand is an observability platform that helps data engineers identify and troubleshoot pipeline issues and data quality problems.

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:---:|:--:|:--:|:--:| 
| ❌ | ? | ? | ? | ❌ | ? | ? | ? | ✔️ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push </li>
<li><b>UX personalization:</b> ?</li> 
<li><b>AI autowiring:</b> ?</li> 
<li><b>Network-based:</b> ?</li> 
<li><b>Rich data profiling:</b> ?</li> 
<li><b>Supported data sources:</b>  </li>
</ul>
</details>

<br>

<a name="datafold"></a>
### Datafold

[Website](https://www.datafold.com/) | [GitHub](https://github.com/datafold)

Datafold is a data monitoring and observability platform.

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:---:|:--:|:--:|:--:| 
| ❌ | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ❌ | ✔️ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Push </li>
<li><b>UX personalization:</b> ?</li> 
<li><b>AI autowiring:</b> ?</li> 
<li><b>Network-based:</b> ?</li> 
<li><b>Rich data profiling:</b> ?</li> 
<li><b>Supported data sources:</b>  </li>
</ul>
</details>

<br> 

<a name="ataccama"></a>
### Ataccama

[Website](https://www.ataccama.com/) | [GitHub](https://github.com/ataccama)

|Based on Open Standard | Search-based | Network-based | Lineage-based | Federation | ML 1st Citizen | Data Quality | End-to-end Lineage | Observability |
|:--:|:---:|:---:|:---:|:--:|:---:|:--:|:---:|:---:| 
| ❌ | ✔️ | ❌  | ✔️ | ❌ | ❌ | ✔️ | ❌ | ❌ |

<details>
<summary>More features</summary>
<br>
<ul>
<li><b>Strategy:</b> Pull </li>
<li><b>UX personalization:</b> Yes</li> 
<li><b>AI autowiring:</b> No</li> 
<li><b>Network-based:</b> No</li> 
<li><b>Rich data profiling:</b> Yes</li> 
<li><b>Supported data sources:</b>  </li>
</ul>
</details>

<br>
