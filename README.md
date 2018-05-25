# 社会主义核心价值观编码解码器

源码来自 https://github.com/sym233/core-values-encoder

## 使用

```html
<script src="shzyhxjzg.js"></script>
<script>
  var happy = shzyhxjzgEncode('开心每一天');
  // --> 诚信自由平等友善平等诚信文明爱国富强诚信自由平等友善平等友善敬业爱国和谐诚信自由公正诚信富强友善敬业爱国诚信平等诚信自由自由友善平等爱国爱国富强友善爱国平等诚信富强自由友善自由敬业

  var how = shzyhxjzgDecode('诚信自由平等友善平等诚信文明爱国富强诚信自由平等友善平等友善敬业爱国和谐诚信自由公正诚信富强友善敬业爱国诚信平等诚信自由自由友善平等爱国爱国富强友善爱国平等诚信富强自由友善自由敬业');
  // --> 开心每一天
</script>
```
