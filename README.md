# DL_Homework
Optimizations:
Model
Window_size
    Ran 1-10 as window sizes and window size 7 performed the best with regards to loss and prediction.
Layer units
    Found a paper on optimized units for a trading model and could not improve on it:
        layer 1 = 75; layer 2 = 30; layer 3 = 30
Dropout Fraction
    Did not try different DFs.
Optimized
    Adam was the best optimizer.  the others gave highly inaccurate graphs.
Loss
    Did not test different loss types.
Epochs
    Tried 10, 100, 1000 epochs.  Ten seemed to have the best results so worked from 10 up to 100 and loss and evaluate optimized at 70 epochs.
Batch Size
    Batch size optimized at 45.
Dense
    Did not try different Densities.
    
FNG vs Closing Model
    Loss was better with the Closing Model than for the FNG Model; accuracy, the same.
        Closing = loss: 0.0039 - accuracy: 0.0062
        FNG = loss: 0.0968 - accuracy: 0.0062
    The Closing model plotted (tracked) better than the FNG model.
    
        