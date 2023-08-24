# Machine Learning for Estimating Standard Formation Proporties of Chemical Compounds

# 🔍 Objective

Performing experimental calculations on chemicals is time-consuming and highly expensive. To expedite this process, various theoretical methods, such as the group contribution method (GCM), have been developed since the 1950s to calculate theoretically the thermodynamic properties of chemicals. However, these methods often remain independent of each other and may not consistently yield accurate results for every compound. Nevertheless, previous research in the field has uncovered a linear correlation between observed and unobserved properties of chemical compounds. Our objective is to develop machine learning models capable of predicting these properties of compounds, aiming to bridge the gap and achieve more accurate predictions.

# 📊 Details of the Project
The goal of this project is to curate datasets from existing literature sources, as well as create new datasets specific to this study. These datasets will undergo appropriate preprocessing to suit the models, which will then be implemented effectively.<br>

<b>Guidelines for the project are as follows:</b><br>
• Code will be commented to enhance comprehension for readers<br>
• Google <b>Colab</b> (utilizing Jupyter notebooks) will be the chosen platform to facilitate efficient code management and tracking<br>
• Each compound included in the dataset will be assigned a <b>CAS</b> or <b>CID</b> number, along with <b>isomeric SMILES</b> representations<br>
• The three phases (gas, liquid, and solid) of <b>Δ<sub>f</sub>H⁰</b>, <b>S⁰</b>, and <b>Cp</b> will be investigated<br>
<br>
<b>The progression of the project involves the following steps:</b><br>
• The utilization of both mixed datasets and segregated datasets categorized into distinct classes is planned<br>
• Experimental data will compose these datasets, serving as a basis for contrasting the model's performance against theoretical calculation methods mentioned in existing literature<br>
• The project encompasses multiple sub-projects within its scope to address these diverse aspects
<p align="center"><b>Table 1</b>: Example of the dataset</p>
<table>
  <tr>
    <th>Name</th>
    <th>Formula</th>
    <th>CAS</th>
    <th>Isomeric Smiles</th>
    <th>Family</th>
    <th>Δ<sub>f</sub>H⁰<sub>gas</sub></th>
    <th>Cp<sub>gas</sub></th>
    <th>S⁰<sub>gas</sub></th>
    <th>Δ<sub>f</sub>H⁰<sub>liq</sub></th>
    <th>Cp<sub>liq</sub></th>
    <th>S⁰<sub>liq</sub></th>
    <th>Δ<sub>f</sub>H⁰<sub>solid</sub></th>
    <th>Cp<sub>solid</sub></th>
    <th>S⁰<sub>solid</sub></th>
  </tr>
  <tr>
    <td>Ethanal</td>
    <td>C2H4O</td>
    <td>75-07-0</td>
    <td>CC=O</td>
    <td>Aldehyde</td>
    <td>-166.1</td>
    <td>54.64</td>
    <td>264.22</td>
    <td>-191.8</td>
    <td>89.1</td>
    <td>117.3</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Ethanamide</td>
    <td>C2H5NO</td>
    <td>60-35-5</td>
    <td>CC(=O)N</td>
    <td>Amides</td>
    <td>-238.3</td>
    <td>63.22</td>
    <td>272.21</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-317.0</td>
    <td>91.3</td>
    <td>115.0</td>
  </tr>
  <tr>
    <td>Acetanilide</td>
    <td>C8H9NO</td>
    <td>103-84-4</td>
    <td>CC(=O)NC1=CC=CC=C1</td>
    <td>Amides</td>
    <td>-128.9</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-209.6</td>
    <td>179.3</td>
    <td>-</td>
  </tr>
</table>

<b>Recommended data for preparing dataset:</b><br>
• Pedley, J. B., Naylor, R. D., and Kirby, S. P. (1986). Thermochemical Data of Organic Compounds. DOI: <a href="https://doi.org/10.1007/978-94-009-4099-4">10.1007/978-94-009-4099-4</a><br>
• Domalski, E. S., and Hearing, E. D. (1993). Estimation of the Thermodynamic Properties of C‐H‐N‐O‐S‐Halogen Compounds at 298.15 K. Journal of Physical and Chemical Reference Data, 22(4), 805–1159. DOI: <a href="https://doi.org/10.1063/1.555927">10.1063/1.555927</a><br>
• National Institute of Standards and Technology (<a href="https://doi.org/10.1063/1.555927">NIST</a>), Thermodynamic Data: Gas phase & Condensed phase

<h2>Additional information can be found in the following sections:<h2>
• Datasets<br>
• Preprocessing<br>
• Models<br>
