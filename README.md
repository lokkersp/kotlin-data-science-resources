# Kotlin Data Science Resources
### Libraries, media, links, and other resources to use Kotlin for data science applications


![](https://camo.githubusercontent.com/705d7144bcce5b0fcb68ea1bd563837bdf3398da/687474703a2f2f692e696d6775722e636f6d2f763346716945412e706e67)

This document serves as an awesome-like curation of helpful links in using Kotlin for data science/data engineering/machine learning/optimization purposes. Please feel free to put in PR's with other links you find helpful. 

Data Science is a [broad, buzzwordy](http://tomstechnicalblog.blogspot.com/2018/01/is-it-time-to-stop-using-term-data.html) domain that seeks to gain insight from data. Arguably, [optimization and operations research](https://cs.stackexchange.com/questions/71525/data-science-vs-operations-research) algorithms play a role in this space as well. While the incumbent programming tools in data science are [R](https://www.r-project.org/), [Python](https://www.python.org/), and even [Scala](http://www.scala-lang.org/), there is a [large opportunity for Kotlin](https://www.youtube.com/watch?v=J8GYPG6pt5w) to enter this space. Kotlin can add value by closing the gap between data science and software engineering, and essentially finish what Scala started. 

With [Kotlin/Native](https://kotlinlang.org/docs/reference/native-overview.html) on the horizon, the scope of this document will hopefully expand beyond the JVM. 

# Showcases

Open-source applications and proof-of-concepts demonstrating data science modeling with Kotlin. 

|Project|Description|
|---|---|
|[Kotlin Math Cheatsheet](https://github.com/thomasnield/kotlin_math_cheatsheet/blob/master/README.md)|How to turn mathematical symbol expressions into Kotlin code|
|[Bayes Email Spam Filter](https://github.com/thomasnield/bayes_email_spam)|A Kotlin proof-of-concept implementation of a spam filter
|[Bayes User Input Prediction](https://github.com/thomasnield/bayes_user_input_prediction)|A simple TornadoFX app that predicts user inputs using Naive Bayes text categorization
|[Classroom Scheduler](https://github.com/thomasnield/optimized-scheduling-demo)|A discrete programming model that schedules classes against one classroom|
|[Sudoku Solver](https://github.com/thomasnield/kotlin-sudoku-solver/blob/master/README.md)|A showcase of constraint programming and discrete optimization|
|[Traveling Salesman Problem](https://github.com/thomasnield/traveling_salesman_demo)|A visual Kotlin demo of the [Traveling Salesman Problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem)|
|[Driver Shift Optimizer](https://github.com/thomasnield/continuous-optimization-example)|A  linear programming model using ojAlgo to minimze the cost of driver shifts in a day
|[Kotlin Simple Neural Network](https://github.com/thomasnield/kotlin_simple_neural_network)|A simple application built with a Kotlin-implemented neural network|
|[Kubed Map Visualization](https://medium.com/@hudsonb/lets-make-a-visualization-choropleth-map-f2a90a82f9b6)|A U.S. heat map of unemployment rates|


# Kotlin Libraries

|Library Name|Category|Description
|---|---|---|
|[Kotlin-Statistics](https://github.com/thomasnield/kotlin-statistics)|Analytics|Idiomatic statistical/analytical extension functions for Kotlin|
|[okAlgo](https://github.com/optimatika/okAlgo)|Optimization|Kotlin extensions to [ojAlgo](https://github.com/optimatika/ojAlgo)|
|[Data2Viz](http://data2viz.io/)|Charts|Cross-platform charts and visuals for Kotlin|
|[Sparklin](https://github.com/khud/sparklin)|Scaled Data Processing|Kotlin framework for Apache Spark|
|[Krangl](https://github.com/holgerbrandl/krangl)|Analytics|[dplyr](https://github.com/tidyverse/dplyr)-like data frame wrangling for Kotlin|
|[Koma](https://github.com/kyonifer/koma)|Computation|Scientific library for Kotlin with interop/multiplatform capabilities|
|[Komputation](https://github.com/sekwiatkowski/komputation)|Deep Learning|Neural network platform for Kotlin, primarily for text processing|
|[KotlinNLP](https://github.com/KotlinNLP)|Natural Language Processing|Natural Language Processing framework for Kotlin|
|[TornadoFX](https://www.gitbook.com/book/edvin/tornadofx-guide/details)|UI, Charts|Kotlin UI desktop app framework, built on top [JavaFX](https://docs.oracle.com/javase/8/javafx/get-started-tutorial/jfx-overview.htm)|
|[TornadoFX-ControlsFX](https://github.com/edvin/tornadofx-controlsfx)|UI|[ControlsFX](http://fxexperience.com/controlsfx/features/) extensions with more data views and controls for TornadoFX|
|[Kotlin Jupyter](https://github.com/ligee/kotlin-jupyter)|Notebook|Kotlin support for Jupyter|
|[JINX](https://exceljava.com/docs/tutorials/kotlin.html)|Plugin|Create Excel functions with Java/Scala/Kotlin instead of VBA|
|[Kotlin Algorithm](https://github.com/gazolla/Kotlin-Algorithm#machine-learning)|Algorithm|Kotlin algorithm implementations|

# Java Libraries

|Library Name|Category|Description|
|---|---|---|
|[DeepLearning4J](https://deeplearning4j.org/)|Deep Learning|Deep learning library for Java|
|[ND4J](http://nd4j.org/)|Computation|Efficient matrix math library for JVM|
|[TableSaw](https://github.com/jtablesaw/tablesaw)|DataFrame|Tabular data processing and manipulation|
|[Joinery](https://cardillo.github.io/joinery/v1.8/api/reference/joinery/DataFrame.html)|DataFrame|Tabular data processing and manipulation|
|[Kubed](https://github.com/hudsonb/kubed)|Visualization|JavaFX-based, [D3.js](https://d3js.org/)-like visualizations|
|[Dex](https://github.com/PatMartin/Dex)|Charting|Java-based data visualization tool|
|[JSoup](https://jsoup.org/)|Data Wrangling|HTML parsing library for Java|
|[Smile](https://github.com/haifengl/smile)|ML and analytics|Comprehensive machine learning, NLP, linear algebra, graph, interpolation, and visualization system|
|[ojAlgo!](http://www.ojalgo.org/)|LP and Optimization|Helpful library for linear/mixed optimization and linear algebra
|[Apache Commons Math](http://commons.apache.org/proper/commons-math/)|Math/Statistics/ML|General math, statistics, and ML library for Java|
|[Apache Commons IO](https://commons.apache.org/proper/commons-io/)|IO|IO Utilities|
|[JBlas](https://github.com/mikiobraun/jblas)|Linear Algebra|Linear Algebra for Java|
|[OptaPlanner](https://www.optaplanner.org/)|Optimization|Solver utility for optimization planning problems|
|[Charts](https://github.com/HanSolo/charts)|Charting|Scientific JavaFX charting library in development|
|[CoreNLP](https://stanfordnlp.github.io/CoreNLP/)|Natural Language Processing|Natural language processing toolkit|
|[Renjin](https://en.wikipedia.org/wiki/Renjin)|Interop|R JVM implementation|
|[Apache Mahout](https://mahout.apache.org/)|Linear Algebra|Distributed framework for regression, clustering and recommendation|
|[Weka](https://www.cs.waikato.ac.nz/ml/index.html)|Data Mining Software|Collection of machine learning algorithms for data mining tasks|

# Resources for Python Developers

If you already are proficient in Python but want to learn Kotlin and its potential on the data science domain. 

|Name|Media|Topic|Description|
|---|---|---|---|
|[From Data Science to Production with Kotlin (O'Reilly)](https://www.safaribooksonline.com/library/view/from-data-science/9781491998205/)|Video|Kotlin|Trains Python data science professionals transitioning to Kotlin|
|[Kotlin for Data Science (KotlinConf)](https://www.youtube.com/watch?v=J8GYPG6pt5w)|Video|Kotlin|KotlinConf session explaining the merits of Kotlin for data science|
|[Kotlin for Python Programmers](https://kotlinfrompython.wordpress.com/contents/)|Blog|Kotlin|Blog relating Kotlin concepts to a Pythonista audience|


# Resources for Kotlin Developers

If you are a veteran JVM/Kotlin developer trying to break into the broad, buzzwordy domain of "data science".

|Name|Media|Topic|Description|
|---|---|---|---|
|[Brandon Rohrer](https://brohrer.github.io/blog.html)|Blog|ML|Excellent videos and articles on machine learning topics|
|[3Blue1Brown](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)|Video|Math, ML, etc|Excellent YouTube channel visually covering mathematical concepts, including neural networks|
[Make Your Own Neural Network](https://www.amazon.com/Make-Your-Own-Neural-Network/dp/1530826608/)|eBook|ML|The best practical guide on neural networks I've found|
|[Python for the Busy Java Developer](https://gumroad.com/l/py4java)|eBook|Python|Helpful resource for Java devs to learn Python quickly|
|[Data Science with Java (O'Reilly)](http://shop.oreilly.com/product/0636920043171.do)|Book|Data Science|Teaches data science for Java developers|
|[Mastering Java for Data Science (Packt)](https://www.amazon.com/Mastering-Java-Data-Science-production-ready/dp/1782174273/)|Book|Data Science|Data science for Java developers|
|[Mastering Java Machine Learning (Packt)](https://www.amazon.com/Mastering-Java-Machine-Learning-architectures/dp/1785880519)|Book|ML|Machine learning for Java developers|
|[Discrete Optimization (Coursera)](https://www.coursera.org/learn/discrete-optimization/)|Online Class|Optimization|Deep dive class into linear/integer programming and optimization|
|[Machine Learning for Absolute Beginners](http://a.co/4Ir0KhJ)|eBook|ML|Excellent eBook to get high level understanding of ML|
|[Model Building in Mathematical Programming](http://a.co/hgXKLKr)|Book|Optimization|Covers linear/integer programming particularly for optimization problems


# Roadmap

For Kotlin to become a mainstream data science platform on par with Python and R, there is still some work to do. This will depend heavily on you, the community, to help fill these gaps. 

- [ ] Kotlin extensions to existing Java libs are an easy contribution opportunity (e.g. Kotlin-Statisitcs and Sparklin)
- [ ] Machine Learning- More robust machine learning libraries/API's need to be integrated with Kotlin (e.g. SMILE)
- [ ] Implement ML algorithms in [Kotlin Algorithm](https://github.com/gazolla/Kotlin-Algorithm#machine-learning) project
- [ ] Kotlin/Native - Explore bindings against Python C libraries
- [ ] Kotlin/Native - Need a NumPy-like library, [ojAlgo](https://github.com/optimatika/ojAlgo)-like solvers a plus
- [ ] Jupyter support- There is a [Jupyter plugin](https://github.com/ligee/kotlin-jupyter) for Kotlin that needs development

# Communities

|Name|Platform|Description|
|---|---|---|
|[PySlackers](https://pyslackers.com/)|Slack|A Slack community of Python developers and data science professionals.|
|[Kotlin Slack](https://kotlinlang.slack.com/messages/C4W52CFEZ)|Slack|A Slack community of Kotlin developers. Join the #datascience channel|

# Blogs, Press, Media

|Name|Media|Description|
|---|---|---|
|[Kotlin Machine Learning  and Optimization](https://www.youtube.com/playlist?list=PLYDlqiU6gadsBEHh-N861iWcBzazs4sEU)|Video|Thomas' demos and walkthroughs of different optimization and machine learning algorithms in Kotlin|
|[KotlinConf- Kotlin for Data Science](https://www.youtube.com/watch?v=J8GYPG6pt5w)|Conference|Thomas Nield explains the merits of Kotlin on the data science domain|
|[KotlinConf - Kscript](https://www.youtube.com/watch?v=cOJPKhlRa8c)|Conference|Holger Brandl covers kscript for data science workflows|
|[Talking Kotlin - Data Science with Thomas Nield](http://talkingkotlin.com/Data-Science-with-Thomas-Nield/)|Podcast|Thomas Nield explains the merits of Kotlin on the data science domain
|[Kotlin's Emerging Data Science Ecosystem](https://holgerbrandl.github.io/kotlin4ds_kotlin_night_frankfurt//emerging_kotlin_ds_ecosystem.html)|Talk/Slides|Holger Brandl gives an update on Kotlin's state as a data science platform|
