This one is a bit annoying because it needs to be retyped/copy-pasted for every new Python notebook. 

Put this alongside the code that imports the libraries you want to use.

    import numpy as np 
    import matplotlib.pyplot as plt
    plt.rcParams.update({'font.size': 16}) 
    plt.rcParams.update({'font.family': 'times-new-roman'})
    plt.rcParams.update({'lines.linewidth': 2})
    plt.style.use('dark_background')
    import savingfigR as sf 
