var xhr = new XMLHttpRequest();
xhr.open('GET', '/img/');
xhr.responseType = 'document';
xhr.onload = function() {
  if (xhr.status === 200) {
    var files = xhr.response.getElementsByTagName('a');
    // 过滤出以 '.jpg' 或 '.png' 结尾的文件
    var imageFiles = Array.prototype.filter.call(files, function(item) {
      return item.href.match(/\.(jpe?g|png)$/i);
    });
    // 打乱排序
    imageFiles.sort(function() {return 0.5 - Math.random()});
    // 选一张随机展示
    var randomImage = imageFiles[0].href;
  } else {
    console.error(xhr.statusText);
  }
};
xhr.onerror = function() {
  console.error(xhr.statusText);
};
xhr.send();
