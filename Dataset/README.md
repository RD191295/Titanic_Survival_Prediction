👋🛳️ Hello Folks ....

This is the legendary Titanic ML competition Dataset From Kaggle competition.The competition is simple: use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

<h2> Overview </h2>
The data has been split into two groups:

<ul>
  <li> training set (train.csv) </li>
  <li> test set (test.csv) </li>
</ul>

<p> The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.</p>

<p>The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.</p>

<h2> Data Dictionary </h2>

<table style="width:547.15pt;margin-left:-48.35pt;background:white;border-collapse: collapse;border:none;">
    <tbody>
        <tr>
            <td style="width: 81.55pt;border: 1pt solid windowtext;background: rgb(68, 114, 196);padding: 6.75pt 18pt 5.25pt;height: 22.55pt;vertical-align: bottom;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:24.0pt;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;border:none windowtext 1.0pt;padding:0cm;'>Variable</span></p>
            </td>
            <td style="width: 189.8pt;border-top: 1pt solid windowtext;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-image: initial;border-left: none;background: rgb(68, 114, 196);padding: 6.75pt 18pt 5.25pt;height: 22.55pt;vertical-align: bottom;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:24.0pt;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;border:none windowtext 1.0pt;padding:0cm;'>Definition</span></p>
            </td>
            <td style="width: 275.8pt;border-top: 1pt solid windowtext;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-image: initial;border-left: none;background: rgb(68, 114, 196);padding: 6.75pt 18pt 5.25pt;height: 22.55pt;vertical-align: bottom;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:24.0pt;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;border:none windowtext 1.0pt;padding:0cm;'>Key</span></p>
            </td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>survival</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>Survival</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>0 = No, 1 = Yes</span></p>
            </td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>pclass</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>****** class</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>1 = 1st, 2 = 2nd, 3 = 3rd</span></p>
            </td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>sex</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>Sex</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;"><br></td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 6.75pt 18pt 5.25pt;height: 10.95pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>Age</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 10.95pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>Age in years</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 10.95pt;vertical-align: top;"><br></td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>sibsp</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'># of siblings / spouses  aboard the Titanic</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;"><br></td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>parch</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'># of parents / children abroad the Titanic</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;"><br></td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>ticket</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>Ticket number</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;"><br></td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 6.75pt 18pt 5.25pt;height: 10.95pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>fare</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 10.95pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>Passenger fare</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 10.95pt;vertical-align: top;"><br></td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>cabin</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>Cabin number</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;"><br></td>
        </tr>
        <tr>
            <td style="border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>embarked</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>Port ** Embarkation</span></p>
            </td>
            <td style="border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 6.75pt 18pt 5.25pt;height: 11.55pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;line-height:normal;font-size:15px;font-family:"Calibri",sans-serif;'><span style='font-size:16px;font-family:"Arial",sans-serif;color:black;'>C = Cherbourg, Q = Queenstown, S = Southampton</span></p>
            </td>
        </tr>
    </tbody>
</table>

<h2> Variable Notes </h2>
<ul>
  <li>pclass: A proxy for socio-economic status (SES)</li>
1st = Upper
2nd = Middle
3rd = Lower

  <li>age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5 </li>
  <li>sibsp: The dataset defines family relations in this way...</li>
  <li>Sibling = brother, sister, stepbrother, stepsister </li>
  <li> Spouse = husband, wife (mistresses and fiancés were ignored) </li>
  <li>parch: The dataset defines family relations in this way...</li>
  <li>Parent = mother, father </li>
  <li>Child = daughter, son, stepdaughter, stepson </li>
  <li>Some children travelled only with a nanny, therefore parch=0 for them.</li>
