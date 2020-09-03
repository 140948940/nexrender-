{
				"module": "@nexrender/action-upload",
				"input": "E:/jieyingAE/wenshen/myresult.mp4",
				"provider": "aliyun",
				"params": {
					"accessKeyId": "****",
					"accessKeySecret": "****",
					"bucket": "***",
					"region": "oss-cn-hangzhou"
				},
				"output": "jieying/liuyingfa1.mp4"
			}
      
      把nexrender谷歌云里面的src里的index.js替换为压缩包内的，文件名改为provider-aliyun（不改也行，和provider保持一致如文件名provider-aliyun，provider为aliyun）
