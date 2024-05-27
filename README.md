# Formula-1-Analysis

Formula 1, renowned for its dynamism and
competitiveness, encompasses diverse variables that sig-
nificantly influence driver performance. Our study aims
to gauge the relevance of F1 race constraints in predict-
ing driver performance. Our approach begins by ana-
lyzing different models like Logistic Regression, Decision-
TreeClassifier, RandomForestClassifier, SVC, GaussianNB
and KNeighborsClassifier using the data of active drivers
and constructors and comparing them to pick a model to
move forward with. We then train the model on data using
both drivers and constructors, only drivers and only con-
structors. Finally, we incorporate race track data by us-
ing their images and leveraging pretrained VGG19 to gen-
erate feature maps of these images. Through the utiliza-
tion of RF-feature importance guided dimensionality reduc-
tion, we obtain our highest-performing model which yields
a testing accuracy of 0.85. Furthermore, employing feature
importance analysis has enabled us to pinpoint the most
informative features crucial in predicting race outcomes.
This strategic mapping back to these influential features en-
hances our understanding of their impact on race predic-
tions.