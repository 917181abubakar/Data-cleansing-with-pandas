<div data-target="readme-toc.content" class="Box-body px-5 pb-5">
          <article class="markdown-body entry-content container-lg" itemprop="text"><div align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/981d48e57e23a4907cebc4eb481799b5882595ea978261f22a3e131dcd6ebee6/68747470733a2f2f70616e6461732e7079646174612e6f72672f7374617469632f696d672f70616e6461732e737667"><img src="https://camo.githubusercontent.com/981d48e57e23a4907cebc4eb481799b5882595ea978261f22a3e131dcd6ebee6/68747470733a2f2f70616e6461732e7079646174612e6f72672f7374617469632f696d672f70616e6461732e737667" data-canonical-src="https://pandas.pydata.org/static/img/pandas.svg" style="max-width: 100%;"></a><br>
</div>
<hr>
<h1 dir="auto"><a id="user-content-pandas-powerful-python-data-analysis-toolkit" class="anchor" aria-hidden="true" href="#pandas-powerful-python-data-analysis-toolkit"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>pandas: powerful Python data analysis toolkit</h1>
<p dir="auto"><a href="https://pypi.org/project/pandas/" rel="nofollow"><img src="https://camo.githubusercontent.com/74cb3c88c43d4266705ae6ec7fddc1bbf603eb6d15bf2202ceb3416cd26b7c0d/68747470733a2f2f696d672e736869656c64732e696f2f707970692f762f70616e6461732e737667" alt="PyPI Latest Release" data-canonical-src="https://img.shields.io/pypi/v/pandas.svg" style="max-width: 100%;"></a>
<a href="https://anaconda.org/anaconda/pandas/" rel="nofollow"><img src="https://camo.githubusercontent.com/3946e75037eae5c757c1f87dca16d9308da064caedba9966f56622d7426a0176/68747470733a2f2f616e61636f6e64612e6f72672f636f6e64612d666f7267652f70616e6461732f6261646765732f76657273696f6e2e737667" alt="Conda Latest Release" data-canonical-src="https://anaconda.org/conda-forge/pandas/badges/version.svg" style="max-width: 100%;"></a>
<a href="https://doi.org/10.5281/zenodo.3509134" rel="nofollow"><img src="https://camo.githubusercontent.com/dc1862109b52a1a02893ed309db67a17104c54b66e050dee3d23c858c2514140/68747470733a2f2f7a656e6f646f2e6f72672f62616467652f444f492f31302e353238312f7a656e6f646f2e333530393133342e737667" alt="DOI" data-canonical-src="https://zenodo.org/badge/DOI/10.5281/zenodo.3509134.svg" style="max-width: 100%;"></a>
<a href="https://pypi.org/project/pandas/" rel="nofollow"><img src="https://camo.githubusercontent.com/caf1bfd611737461f1d62e150d6753e05602727131be954051dd3a41dc901101/68747470733a2f2f696d672e736869656c64732e696f2f707970692f7374617475732f70616e6461732e737667" alt="Package Status" data-canonical-src="https://img.shields.io/pypi/status/pandas.svg" style="max-width: 100%;"></a>
<a href="https://github.com/pandas-dev/pandas/blob/main/LICENSE"><img src="https://camo.githubusercontent.com/810dee2f0ccde96614200a43630598d77394709e8699d531d6c6f7bbaaf53841/68747470733a2f2f696d672e736869656c64732e696f2f707970692f6c2f70616e6461732e737667" alt="License" data-canonical-src="https://img.shields.io/pypi/l/pandas.svg" style="max-width: 100%;"></a>
<a href="https://dev.azure.com/pandas-dev/pandas/_build/latest?definitionId=1&amp;branch=main" rel="nofollow"><img src="https://camo.githubusercontent.com/1a06638143592e911b12f208c06b802f84e050ebb072cb5da382fa93251a7ed2/68747470733a2f2f6465762e617a7572652e636f6d2f70616e6461732d6465762f70616e6461732f5f617069732f6275696c642f7374617475732f70616e6461732d6465762e70616e6461733f6272616e63683d6d61696e" alt="Azure Build Status" data-canonical-src="https://dev.azure.com/pandas-dev/pandas/_apis/build/status/pandas-dev.pandas?branch=main" style="max-width: 100%;"></a>
<a href="https://codecov.io/gh/pandas-dev/pandas" rel="nofollow"><img src="https://camo.githubusercontent.com/dc3022dfb3ac78ef27a8624e84c81959c91f71933572607ab062992707c4feac/68747470733a2f2f636f6465636f762e696f2f6769746875622f70616e6461732d6465762f70616e6461732f636f7665726167652e7376673f6272616e63683d6d61696e" alt="Coverage" data-canonical-src="https://codecov.io/github/pandas-dev/pandas/coverage.svg?branch=main" style="max-width: 100%;"></a>
<a href="https://pepy.tech/project/pandas" rel="nofollow"><img src="https://camo.githubusercontent.com/5b1c7be9058d78c455dc07ff2d2da7f4042ddafb85d1061a88ff11be195dcd23/68747470733a2f2f7374617469632e706570792e746563682f706572736f6e616c697a65642d62616467652f70616e6461733f706572696f643d6d6f6e746826756e6974733d696e7465726e6174696f6e616c5f73797374656d266c6566745f636f6c6f723d626c61636b2672696768745f636f6c6f723d6f72616e6765266c6566745f746578743d50795049253230646f776e6c6f6164732532307065722532306d6f6e7468" alt="Downloads" data-canonical-src="https://static.pepy.tech/personalized-badge/pandas?period=month&amp;units=international_system&amp;left_color=black&amp;right_color=orange&amp;left_text=PyPI%20downloads%20per%20month" style="max-width: 100%;"></a>
<a href="https://gitter.im/pydata/pandas" rel="nofollow"><img src="https://camo.githubusercontent.com/5dbac0213da25c445bd11f168587c11a200ba153ef3014e8408e462e410169b3/68747470733a2f2f6261646765732e6769747465722e696d2f4a6f696e253230436861742e737667" alt="Gitter" data-canonical-src="https://badges.gitter.im/Join%20Chat.svg" style="max-width: 100%;"></a>
<a href="https://numfocus.org" rel="nofollow"><img src="https://camo.githubusercontent.com/42ca0da5f59b4fa9dd410434fa62cf8942c437d06669273fa7783c15d1be9cee/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f706f776572656425323062792d4e756d464f4355532d6f72616e67652e7376673f7374796c653d666c617426636f6c6f72413d45313532334426636f6c6f72423d303037443841" alt="Powered by NumFOCUS" data-canonical-src="https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&amp;colorA=E1523D&amp;colorB=007D8A" style="max-width: 100%;"></a>
<a href="https://github.com/psf/black"><img src="https://camo.githubusercontent.com/d91ed7ac7abbd5a6102cbe988dd8e9ac21bde0a73d97be7603b891ad08ce3479/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636f64652532307374796c652d626c61636b2d3030303030302e737667" alt="Code style: black" data-canonical-src="https://img.shields.io/badge/code%20style-black-000000.svg" style="max-width: 100%;"></a>
<a href="https://pycqa.github.io/isort/" rel="nofollow"><img src="https://camo.githubusercontent.com/fe4a658dd745f746410f961ae45d44355db1cc0e4c09c7877d265c1380248943/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f253230696d706f7274732d69736f72742d2532333136373462313f7374796c653d666c6174266c6162656c436f6c6f723d656638333336" alt="Imports: isort" data-canonical-src="https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&amp;labelColor=ef8336" style="max-width: 100%;"></a></p>
<h2 dir="auto"><a id="user-content-what-is-it" class="anchor" aria-hidden="true" href="#what-is-it"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>What is it?</h2>
<p dir="auto"><strong>pandas</strong> is a Python package that provides fast, flexible, and expressive data
structures designed to make working with "relational" or "labeled" data both
easy and intuitive. It aims to be the fundamental high-level building block for
doing practical, <strong>real world</strong> data analysis in Python. Additionally, it has
the broader goal of becoming <strong>the most powerful and flexible open source data
analysis / manipulation tool available in any language</strong>. It is already well on
its way towards this goal.</p>
<h2 dir="auto"><a id="user-content-main-features" class="anchor" aria-hidden="true" href="#main-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Main Features</h2>
<p dir="auto">Here are just a few of the things that pandas does well:</p>
<ul dir="auto">
<li>Easy handling of <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/missing_data.html" rel="nofollow"><strong>missing data</strong></a> (represented as
<code>NaN</code>, <code>NA</code>, or <code>NaT</code>) in floating point as well as non-floating point data</li>
<li>Size mutability: columns can be <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/dsintro.html#column-selection-addition-deletion" rel="nofollow"><strong>inserted and
deleted</strong></a> from DataFrame and higher dimensional
objects</li>
<li>Automatic and explicit <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/dsintro.html?highlight=alignment#intro-to-data-structures" rel="nofollow"><strong>data alignment</strong></a>: objects can
be explicitly aligned to a set of labels, or the user can simply
ignore the labels and let <code>Series</code>, <code>DataFrame</code>, etc. automatically
align the data for you in computations</li>
<li>Powerful, flexible <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/groupby.html#group-by-split-apply-combine" rel="nofollow"><strong>group by</strong></a> functionality to perform
split-apply-combine operations on data sets, for both aggregating
and transforming data</li>
<li>Make it <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/dsintro.html#dataframe" rel="nofollow"><strong>easy to convert</strong></a> ragged,
differently-indexed data in other Python and NumPy data structures
into DataFrame objects</li>
<li>Intelligent label-based <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#slicing-ranges" rel="nofollow"><strong>slicing</strong></a>, <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/advanced.html#advanced" rel="nofollow"><strong>fancy
indexing</strong></a>, and <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#boolean-indexing" rel="nofollow"><strong>subsetting</strong></a> of
large data sets</li>
<li>Intuitive <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html#database-style-dataframe-or-named-series-joining-merging" rel="nofollow"><strong>merging</strong></a> and <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html#joining-on-index" rel="nofollow"><strong>joining</strong></a> data
sets</li>
<li>Flexible <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/reshaping.html" rel="nofollow"><strong>reshaping</strong></a> and <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/reshaping.html" rel="nofollow"><strong>pivoting</strong></a> of
data sets</li>
<li><a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#hierarchical-indexing-multiindex" rel="nofollow"><strong>Hierarchical</strong></a> labeling of axes (possible to have multiple
labels per tick)</li>
<li>Robust IO tools for loading data from <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html#csv-text-files" rel="nofollow"><strong>flat files</strong></a>
(CSV and delimited), <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html#excel-files" rel="nofollow"><strong>Excel files</strong></a>, <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html#sql-queries" rel="nofollow"><strong>databases</strong></a>,
and saving/loading data from the ultrafast <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html#hdf5-pytables" rel="nofollow"><strong>HDF5 format</strong></a></li>
<li><a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/timeseries.html#time-series-date-functionality" rel="nofollow"><strong>Time series</strong></a>-specific functionality: date range
generation and frequency conversion, moving window statistics,
date shifting and lagging</li>
</ul>
<h2 dir="auto"><a id="user-content-where-to-get-it" class="anchor" aria-hidden="true" href="#where-to-get-it"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Where to get it</h2>
<p dir="auto">The source code is currently hosted on GitHub at:
<a href="https://github.com/pandas-dev/pandas">https://github.com/pandas-dev/pandas</a></p>
<p dir="auto">Binary installers for the latest released version are available at the <a href="https://pypi.org/project/pandas" rel="nofollow">Python
Package Index (PyPI)</a> and on <a href="https://docs.conda.io/en/latest/" rel="nofollow">Conda</a>.</p>
<div class="highlight highlight-source-shell position-relative overflow-auto"><pre><span class="pl-c"><span class="pl-c">#</span> conda</span>
conda install pandas</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# conda
conda install pandas" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="highlight highlight-source-shell position-relative overflow-auto"><pre><span class="pl-c"><span class="pl-c">#</span> or PyPI</span>
pip install pandas</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# or PyPI
pip install pandas" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 dir="auto"><a id="user-content-dependencies" class="anchor" aria-hidden="true" href="#dependencies"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Dependencies</h2>
<ul dir="auto">
<li><a href="https://www.numpy.org" rel="nofollow">NumPy - Adds support for large, multi-dimensional arrays, matrices and high-level mathematical functions to operate on these arrays</a></li>
<li><a href="https://dateutil.readthedocs.io/en/stable/index.html" rel="nofollow">python-dateutil - Provides powerful extensions to the standard datetime module</a></li>
<li><a href="https://github.com/stub42/pytz">pytz - Brings the Olson tz database into Python which allows accurate and cross platform timezone calculations</a></li>
</ul>
<p dir="auto">See the <a href="https://pandas.pydata.org/pandas-docs/stable/install.html#dependencies" rel="nofollow">full installation instructions</a> for minimum supported versions of required, recommended and optional dependencies.</p>
<h2 dir="auto"><a id="user-content-installation-from-sources" class="anchor" aria-hidden="true" href="#installation-from-sources"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Installation from sources</h2>
<p dir="auto">To install pandas from source you need <a href="https://cython.org/" rel="nofollow">Cython</a> in addition to the normal
dependencies above. Cython can be installed from PyPI:</p>
<div class="highlight highlight-source-shell position-relative overflow-auto"><pre>pip install cython</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install cython" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">In the <code>pandas</code> directory (same one where you found this file after
cloning the git repo), execute:</p>
<div class="highlight highlight-source-shell position-relative overflow-auto"><pre>python setup.py install</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python setup.py install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">or for installing in <a href="https://pip.pypa.io/en/latest/cli/pip_install/#install-editable" rel="nofollow">development mode</a>:</p>
<div class="highlight highlight-source-shell position-relative overflow-auto"><pre>python -m pip install -e <span class="pl-c1">.</span> --no-build-isolation --no-use-pep517</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python -m pip install -e . --no-build-isolation --no-use-pep517" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">If you have <code>make</code>, you can also use <code>make develop</code> to run the same command.</p>
<p dir="auto">or alternatively</p>
<div class="highlight highlight-source-shell position-relative overflow-auto"><pre>python setup.py develop</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python setup.py develop" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">See the full instructions for <a href="https://pandas.pydata.org/pandas-docs/stable/install.html#installing-from-source" rel="nofollow">installing from source</a>.</p>
<h2 dir="auto"><a id="user-content-license" class="anchor" aria-hidden="true" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>License</h2>
<p dir="auto"><a href="/pandas-dev/pandas/blob/main/LICENSE">BSD 3</a></p>
<h2 dir="auto"><a id="user-content-documentation" class="anchor" aria-hidden="true" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Documentation</h2>
<p dir="auto">The official documentation is hosted on PyData.org: <a href="https://pandas.pydata.org/pandas-docs/stable" rel="nofollow">https://pandas.pydata.org/pandas-docs/stable</a></p>
<h2 dir="auto"><a id="user-content-background" class="anchor" aria-hidden="true" href="#background"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Background</h2>
<p dir="auto">Work on <code>pandas</code> started at <a href="https://www.aqr.com/" rel="nofollow">AQR</a> (a quantitative hedge fund) in 2008 and
has been under active development since then.</p>
<h2 dir="auto"><a id="user-content-getting-help" class="anchor" aria-hidden="true" href="#getting-help"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Getting Help</h2>
<p dir="auto">For usage questions, the best place to go to is <a href="https://stackoverflow.com/questions/tagged/pandas" rel="nofollow">StackOverflow</a>.
Further, general questions and discussions can also take place on the <a href="https://groups.google.com/forum/?fromgroups#!forum/pydata" rel="nofollow">pydata mailing list</a>.</p>
<h2 dir="auto"><a id="user-content-discussion-and-development" class="anchor" aria-hidden="true" href="#discussion-and-development"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Discussion and Development</h2>
<p dir="auto">Most development discussions take place on GitHub in this repo. Further, the <a href="https://mail.python.org/mailman/listinfo/pandas-dev" rel="nofollow">pandas-dev mailing list</a> can also be used for specialized discussions or design issues, and a <a href="https://gitter.im/pydata/pandas" rel="nofollow">Gitter channel</a> is available for quick development related questions.</p>
<h2 dir="auto"><a id="user-content-contributing-to-pandas-" class="anchor" aria-hidden="true" href="#contributing-to-pandas-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Contributing to pandas <a href="https://www.codetriage.com/pandas-dev/pandas" rel="nofollow"><img src="https://camo.githubusercontent.com/d632fd4c1dc445316d6578b1d9811a1be26f9badd038f3266f7237aaf0377af4/68747470733a2f2f7777772e636f64657472696167652e636f6d2f70616e6461732d6465762f70616e6461732f6261646765732f75736572732e737667" alt="Open Source Helpers" data-canonical-src="https://www.codetriage.com/pandas-dev/pandas/badges/users.svg" style="max-width: 100%;"></a></h2>
<p dir="auto">All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.</p>
<p dir="auto">A detailed overview on how to contribute can be found in the <strong><a href="https://pandas.pydata.org/docs/dev/development/contributing.html" rel="nofollow">contributing guide</a></strong>.</p>
<p dir="auto">If you are simply looking to start working with the pandas codebase, navigate to the <a href="https://github.com/pandas-dev/pandas/issues">GitHub "issues" tab</a> and start looking through interesting issues. There are a number of issues listed under <a href="https://github.com/pandas-dev/pandas/issues?labels=Docs&amp;sort=updated&amp;state=open">Docs</a> and <a href="https://github.com/pandas-dev/pandas/issues?labels=good+first+issue&amp;sort=updated&amp;state=open">good first issue</a> where you could start out.</p>
<p dir="auto">You can also triage issues which may include reproducing bug reports, or asking for vital information such as version numbers or reproduction instructions. If you would like to start triaging issues, one easy way to get started is to <a href="https://www.codetriage.com/pandas-dev/pandas" rel="nofollow">subscribe to pandas on CodeTriage</a>.</p>
<p dir="auto">Or maybe through using pandas you have an idea of your own or are looking for something in the documentation and thinking ‘this can be improved’...you can do something about it!</p>
<p dir="auto">Feel free to ask questions on the <a href="https://groups.google.com/forum/?fromgroups#!forum/pydata" rel="nofollow">mailing list</a> or on <a href="https://gitter.im/pydata/pandas" rel="nofollow">Gitter</a>.</p>
<p dir="auto">As contributors and maintainers to this project, you are expected to abide by pandas' code of conduct. More information can be found at: <a href="https://github.com/pandas-dev/pandas/blob/main/.github/CODE_OF_CONDUCT.md">Contributor Code of Conduct</a></p>
</article>
        </div>
