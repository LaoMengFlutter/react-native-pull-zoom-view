# react-native-pull-zoom-view



使用：

1、在终端进入到项目目录：npm i react-native-pull-zoom-view --save

2、实例：

    import React, {Component} from 'react';
    import {
        StyleSheet,
        View,
        Dimensions,
    } from 'react-native';
    import PullZoomScrollView from 'react-native-pull-zoom-view'
    var {height, width} = Dimensions.get('window');

    export default class Demo extends Component {
        render() {
            return (
                <View style={{flex: 1}}>
                    <PullZoomScrollView
                        imageHeight={300}
                        minHeight={250}
                        source={require('./s63.png')}>
                        <View style={{height:100,width:width,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                        <View style={{height:100,width:width,marginTop:10,backgroundColor:'red'}}></View>
                    </PullZoomScrollView>
                </View>
            );
        }
    }


3、

   imageHeight: 图片的高度

   source: 图片资源

   minHeight: 最小高度

   
