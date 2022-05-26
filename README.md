# sort spreadsheet (python)
# A function, written in python, designed to scan spreadsheets and sort the values in one specified column by the values in another specified column
  This function returns a dataframe where the column names are the unique values in the spreadsheet's "categories_column" (specified in the function), and the values in each column are the unique values in the spreadsheet's  "subcategories_column" (specified in the function) that coorespond to values in the spreadsheet's "categories_column".
  # Arguments:
    # "spreadsheet" = a dataframe containing data to be sorted
    # "categorization_vector" = an array of categories by which to sort the data
       The categorization_vector will be the dataframe's column names 
    # "categories_column_position" = a numeric value denoting the position of the column containing the values
       by which spreadsheet will be sorted
    # "subcategories_column_position" = a numeric value denoting the position of the column containing the values
       that will be sorted 
       The values in this column will make up the values in the dataframe 
