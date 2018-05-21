# Machine Learning Techniques, Spring 2018, Project
> Links
> + [mltech18spring/project](https://www.csie.ntu.edu.tw/~htlin/course/mltech18spring/project/)
> + [Book-Crossing Dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/)
>     + 資料格式描述
>     + [CSV Dump [25.475 KB]](http://www2.informatik.uni-freiburg.de/~cziegler/BX/BX-CSV-Dump.zip)
>         + 尚不確定跟traning set的關係
>         + 1149780筆評分
>         + 271379本書
>         + 278858使用者
> + [learning2read.slack.com](https://learning2read.slack.com/)
> + [Add short codes prefixes for commits to style guide](https://github.com/quantopian/zipline/issues/96)
>     + SciPy/NumPy所使用加在commit message前的短語

# TODO
1. plot.py
2. setup.py
3. Installation

# Machine Learning Packages/Classes (WIP)

Type|Package|Description
-|-|-
probability|sklearn.linear_model.LogisticRegression|MLE Estimator

# Installation (WIP)
## (copy from pyecharts)
`
git clone https://github.com/pyecharts/pyecharts.git
cd pyecharts
pip install -r requirements.txt
python setup.py install
`

## (windows)
`mklink /d homework "I:\Dropbox\_a5_Projects\homework"`
`mklink /d src dst`

## (osx / linux)
`ln -s /Users/qtwu/Dropbox/_a5_Projects/pytalk/ ./pytalk`
`ln -s dst src`