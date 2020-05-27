<h1> HR Churn prediction </h1>
<p> </p>
<h3>I have a dataset with information about employees, which includes satisfaction level (from 0 to 1), level of salary (low, medium, high), department (HR, IT, sales etc), average working hours and some other characteristics. Also there is information about churn (column 'left', 1 if employee left company and 0 if employee stayed. </h3>
<h3> <i> My goal </i> is churn prediction: whether an employee with a specific salary, level of satisfaction, etc., will leave the company </h3>
<p></p>
<h3> Workinh process </h3>
<h4> I tryed several classification models (I used classififcation, becouse i have the task of dividing the staff into two classes known in advance: those who leave the company and those who remain): </h4>
<ul>
  <li> Logistic regression</li>
  <li> SVM </li>
  <li> Decision Tree Classifier </li>
  <li> Random Tree Classifier </li>
 </ul>
 <h4> Thanks to GridSearchCV and RandomizedSearchTV I optimezed accuracy of models to 95%+, but I had overfitting.</h4>
 <h4> <b> As a result </b> Randomized Tree Regressor has the best accuracy - 98%. We can almost exactly predict the dismissal of an employee </h4>
 <h3> Result </h3>
 <h4>An HR specialist will be able to understand who should be focused right now, with whom is enough hold a motivational conversation, and to whom to offer more serious help, for example, change a mentor or transfer to another project. Also it can reduce the cost of finding new employees</h4>
 
