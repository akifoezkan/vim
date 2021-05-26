my preferred options 

```viml
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""" 
" YouCompleteMe settings                                                         
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""" 
let g:ycm_auto_trigger = 1                                                                       
let g:ycm_confirm_extra_conf = 0                                                 
let g:ycm_autoclose_preview_window_after_completion = 1                          
let g:ycm_global_ycm_extra_conf = '~/.ycm_extra_conf.py'                         
let g:ycm_key_list_select_completion = ['<C-Space>', '<Down>', '<Enter>']        
let g:ycm_key_list_previous_completion = ['<C-S-Space>', '<Up>']                 
let g:EclimCompletionMethod = 'omnifunc'                                         
nnoremap <C-G> :YcmCompleter GoTo<CR>                                            
nnoremap <C-H> :YcmCompleter GoToDeclaration<CR>  
```
