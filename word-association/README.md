Instructions to verify word association bias in text:

1) Create word embeddings using create_word_embedding_utils.R
	csv_name = path to csv containing text data
	num_iter = number of models to be created
	analogias_file = path to file containing analogies to be executed by each model

2) Run bias_detect.R to detect biases in text according to previously created embedding models
	noticias = path to text csv of a news portal
	binary_path = path to binary file containing word embedding models
	output_* = output of candidates and parties bias
	automatic_set_construction = TRUE for construct attribut sets automatically, FALSE otherwise

3) Run data_analysis.Rmd to verify existent biases in the texts
	
	