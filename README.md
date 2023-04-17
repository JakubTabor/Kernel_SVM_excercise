# Kernel_SVM_excercise
# When I get my "X" and "y" prepared i can import "train_test_split" and get "train" and "test" set
# Then I import "StandardScaler" and prepare my "X_train" and "X_test" """X_train = sc.fit_transform(X_train)""" """X_test = sc.transform(X_test)"""
# Next I import "SVC" and set "kernel" at "rbf" """classifier = SVC(kernel='rbf', random_state=0)""", then train my model """classifier.fit(X_train, y_train)"""
