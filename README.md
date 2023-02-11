# CLASSIFICATION OF ANTIDEPRESSANT DRUGS USING THE 1D-CONVNET MODEL
<p>✏️ This source code solves problems regarding the classification of antidepressant drugs into SSRI and Atypical groups using a derivative of the CNN architecture, namely the 1D-Convnet Model. The dataset contains 768 data consisting of 385 SSRI groups and 383 atypical groups.<br/>
✏️ The dataset comes from the site https://go.drugbank.com/ which is collected in text form and stored at https://drive.google.com/drive/folders/1LnxifM_r_qYhaHL5VLfCtoDmIQWGtut8?usp=share_link.</p>

## Visualization of train / test split
<table>
  <tr>
    <td>
      <img alt="Stars" src="https://user-images.githubusercontent.com/124945882/218237081-44e1d3cc-bb05-4857-8559-5432105880a1.png"/>
    </td>
    <td>
      The dataset is divided into training data and test data with a size of 70%:30%.<br/>The number of datasets used for model training is 537 data while for model testing there are 231 data.
    </td>
  </tr>
</table>
 

## Visualization of accuracy and loss
![image](https://user-images.githubusercontent.com/124945882/218235570-5fb8b20d-64de-48c8-a0de-26e71a5ab1cb.png)

## Classification Data
<table>
  <thead align="center">
    <tr border: none;>
      <td><b>Before Preprocessing</b></td>
      <td><b>After Preprocessing</b></td>
      <td><b>Result</b></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Asenapine Tablet 5 mg (Schizophrenia, Bipolar 1 Disorder, Acute Manic Episode, Mixed Manic Depressive Disorder</td>
      <td>[236, 6, 2, 10, 11, 1, 7, 9, 4, 17, 9, 3, 4, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]</td>
      <td>[0] or Atypical</td>
    </tr>
	  <tr>
      <td>PMSC-escitalopram Tablet 5 mg (Mayor Depressive Disorder, Obsessive Compulsif Disorder, Generalized Anxiety Disorder, Social Anxiety Disorder)</td>
      <td>[98, 2, 6, 12, 3, 1, 22, 77, 1, 26, 5, 1, 24, 5, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]</td>
      <td>[1] or SSRI</td>
    </tr>
    <tr>
      <td>Auro-Lurasidone Tablet 100 mg (Schizophrenia, Bipolar, Depression)</td>
      <td>[6, 2, 10, 11, 18, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]</td>
      <td>[0] or Atypical</td>
    </tr>
  </tbody>
</table>
