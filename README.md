
    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text">
<h1><a id="user-content-supervised-learning" class="anchor" href="#supervised-learning" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Supervised Learning</h1>
<h2><a id="user-content-project-finding-donors-for-charityml" class="anchor" href="#project-finding-donors-for-charityml" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Project: Finding Donors for CharityML</h2>
<h3><a id="user-content-install" class="anchor" href="#install" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Install</h3>
<p>This project requires <strong>Python 2.7</strong> and the following Python libraries installed:</p>
<ul>
<li><a href="http://www.numpy.org/">NumPy</a></li>
<li><a href="http://pandas.pydata.org">Pandas</a></li>
<li><a href="http://matplotlib.org/">matplotlib</a></li>
<li><a href="http://scikit-learn.org/stable/">scikit-learn</a></li>
</ul>
<p>You will also need to have software installed to run and execute an <a href="http://ipython.org/notebook.html">iPython Notebook</a></p>
<p>We recommend students install <a href="https://www.continuum.io/downloads">Anaconda</a>, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.</p>
<h3><a id="user-content-code" class="anchor" href="#code" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Code</h3>
<p>Template code is provided in the <code>finding_donors.ipynb</code> notebook file. You will also be required to use the included <code>visuals.py</code> Python file and the <code>census.csv</code> dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in <code>visuals.py</code> is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.</p>
<h3><a id="user-content-run" class="anchor" href="#run" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Run</h3>
<p>In a terminal or command window, navigate to the top-level project directory <code>finding_donors/</code> (that contains this README) and run one of the following commands:</p>
<div class="highlight highlight-source-shell"><pre>ipython notebook finding_donors.ipynb</pre></div>
<p>or</p>
<div class="highlight highlight-source-shell"><pre>jupyter notebook finding_donors.ipynb</pre></div>
<p>This will open the iPython Notebook software and project file in your browser.</p>
<h3><a id="user-content-data" class="anchor" href="#data" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Data</h3>
<p>The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper <em>"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",</em> by Ron Kohavi. You may find this paper <a href="https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf">online</a>, with the original dataset hosted on <a href="https://archive.ics.uci.edu/ml/datasets/Census+Income">UCI</a>.</p>
<p><strong>Features</strong></p>
<ul>
<li><code>age</code>: Age</li>
<li><code>workclass</code>: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)</li>
<li><code>education_level</code>: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)</li>
<li><code>education-num</code>: Number of educational years completed</li>
<li><code>marital-status</code>: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)</li>
<li><code>occupation</code>: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)</li>
<li><code>relationship</code>: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)</li>
<li><code>race</code>: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)</li>
<li><code>sex</code>: Sex (Female, Male)</li>
<li><code>capital-gain</code>: Monetary Capital Gains</li>
<li><code>capital-loss</code>: Monetary Capital Losses</li>
<li><code>hours-per-week</code>: Average Hours Per Week Worked</li>
<li><code>native-country</code>: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&amp;Tobago, Peru, Hong, Holand-Netherlands)</li>
</ul>
<p><strong>Target Variable</strong></p>
<ul>
<li><code>income</code>: Income Class (&lt;=50K, &gt;50K)</li>
</ul>
</article>
  </div>

</html>

