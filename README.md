# TagTextView
文字前面含有标签的TextView

## 导入方法 [![](https://jitpack.io/v/yinjinyj/TagTextView.svg)](https://jitpack.io/#yinjinyj/TagTextView)


    allprojects {
    		repositories {
    			...
    			maven { url 'https://jitpack.io' }
    		}
    	}
    	
    dependencies {
    	        implementation 'com.github.yinjinyj:TagTextView:Tag'
    	}

## 使用方法

~~~kotlin

    flag_text_view.flagTextSize=16
    flag_text_view.flagTextColor= Color.RED
    flag_text_view.setFlagBgPadding(intArrayOf(6,2,6,2))
    flag_text_view.contentColor = Color.BLACK
    flag_text_view.contentTextSize=16
    flag_text_view.setFlagAndContentSpace(6)
    flag_text_view.maxLine=2
    flag_text_view.flagText = "京东超时"
    flag_text_view.content="如果您认为这个讯息是错误的,如果您认为这个讯息是错误的,如果您认为这个讯息是错误的,如果您认为这个讯息是错误的,如果您认为这个讯息是错误的,如果您认为这个讯息是错误的"
    img_flag_text_view.contentColor = Color.BLACK
    img_flag_text_view.flagBitMap=BitmapFactory.decodeResource(resources,R.drawable.icon_notice)
    img_flag_text_view.setBitmapSize(40,40)
    img_flag_text_view.contentTextSize=16
    img_flag_text_view.setFlagAndContentSpace(6)
    img_flag_text_view.maxLine=8
    img_flag_text_view.content="这部剧整体都很像美剧风格，包括跟死者出现那段，我也在美剧中看到过类似的。我还是喜欢第一部法医秦明，不过这部我也还能接受，虽然真的不太像法医，因为拍法医剧，应该着重拍摄法医如何在死者身上发现线索，这部剧不是，这部更像是一部侦探推理剧，法医知识成了点缀，然后刑侦大队的警察则变蠢了，我知道这是剧情需要，但总觉得不该用这种方式突出主角。下次可以参考一下美剧《识骨追踪》和《逝者之证》，这两部都是以法医为主角。还有美剧《CSI》系列"
     

~~~