修改主题copyligt自动获取当前年份的方法
修改主题/www/twonav/templates/home/tushan2/view/index.html
  
`{$copyright|raw} . Theme By demo . {$ICP|raw}`
  为
`© <?php echo date("Y"); ?> demo.com . Theme By ahtu`


搞定收工
