"Hear you human, Tyr brings froth some trained model for you to test with, of course it is on the command of the Odin"
"Just follow the steps and type this in your jupyter notebook"
//////////////////////////////////////////////////

import pickle
loaded_model = pickle.load(open(filename, 'rb'))
result = loaded_model.score(X_test, Y_test)

/////////////////////////////////////////////////

"replace *filename* with the name of the model"
