# nipype-install-error
#nipype installation error solved in windows 10
click start -> windows icon -> Anaconda3 ->
Anaconda Navigator,
click 'Environments',
click button 'Channel'
remove the channel 
In my case gadgetron (channel   had an issue)
update channels (conda-forge, or default) save exit.
Type in the anaconda prompt (console)

conda install -c https://conda.anaconda.org/conda-forge nipype
