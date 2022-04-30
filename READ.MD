# THIS CHECKERBOARD ALLOWS DIFFERENT ROUTES DO DIFFERENT THINGS 
# @app.route('/'): allows a 8 by 8, black and red to appear
# @app.route('/<int:x>': allows you enter whatever amount of set of rows(x) but the 8 columns and colors remain; a x by 8 black and red checkerboard should appear 
# @app.route('/<int:x>/<int:y>'): allows you to set whatever amount of rows(x) and columns(y) but the colors remain; a x by y black and red checkerboard should appear 
# @app.route('/<int:x>/<int:y>/<string:one>'): allows you to set whatever amount of rows(x) and columns(y) and one color but one color(black) remains; a x by y, your choice of color and black checkerboard should appear
# @app.route('/<int:x>/<int:y>/<string:one>/<string:two>'): allows you to set whatever amount of rows(x) and columns(y) and both colors; a x by y both of your choices of color checkerboard should appear