VSN定义
===


## TAG

FileSource: 资源TAG

Resource_ID: 素材ID

FilePath： 原始资源地址

ConvertPath: 转码资源地址.  (只有经过转码过后的资源才有该属性)



```xml
<?xml version="1.0" encoding="utf-8"?>

<Programs> 
  <Program>
    <Information>
      <Width>512</Width>  
      <Height>256</Height>  
      <Scale>1</Scale> 
    </Information>  
    <Pages>
      <Page>
        <AppointDuration>3600000</AppointDuration>  
        <Opacity>1</Opacity>  
        <LoopType>1</LoopType>  
        <BgColor>0xFF000000</BgColor>  
        <Regions>
          <Region>
            <type>3</type>  
            <Layer>1</Layer>  
            <Rect>
              <X>0</X>  
              <Y>0</Y>  
              <Width>512</Width>  
              <Height>256</Height>  
              <BorderWidth>0</BorderWidth>  
              <BorderColor>#ffff00</BorderColor> 
            </Rect>  
            <Name>File_Window</Name>  
            <IsScheduleRegion>0</IsScheduleRegion>  
            <Items>
              <Item>
                <Type>3</Type>  
                <Duration>5000</Duration>  
                <PlayTimes>1</PlayTimes>  
                <Volume>1.000000</Volume>  
                <Loop>1</Loop>  
                <PlayLength>121000</PlayLength>  
                <Schedule>
                  <IsLimitTime>0</IsLimitTime>  
                  <StartTime>00:00:00</StartTime>  
                  <EndTime>23:59:59</EndTime>  
                  <IsLimitDate>0</IsLimitDate>  
                  <StartDay>2018/12/03</StartDay>  
                  <StartDayTime>00:00:00</StartDayTime>  
                  <EndDay>2019/12/03</EndDay>  
                  <EndDayTime>23:59:59</EndDayTime>  
                  <IsLimitWeek>0</IsLimitWeek>  
                  <LimitWeek>1,1,1,1,1,1,1</LimitWeek> 
                </Schedule>  
                <Trigger>
                  <Type>lightStrip</Type>  
                  <Value>0</Value> 
                </Trigger>  
                <FileSource>
                  <IsRelative>1</IsRelative>  
                  <FilePath>.\_Res_.files\F_8627B38BA221B6DFECFE4091F91A3D01_4575087.mp4</FilePath>  
                  <Resource_ID>293311</Resource_ID>  
                  <OriginName>H265_1080.mp4</OriginName>  
                  <ConvertPath>.\_Res_.files\convert-F_8627B38BA221B6DFECFE4091F91A3D01_4575087.mp4</ConvertPath> 
                </FileSource>  
                <ReserveAS>0</ReserveAS> 
              </Item>  
              <Item>
                <Type>3</Type>  
                <Duration>5000</Duration>  
                <PlayTimes>1</PlayTimes>  
                <Volume>1.000000</Volume>  
                <Loop>1</Loop>  
                <PlayLength>121000</PlayLength>  
                <Schedule>
                  <IsLimitTime>0</IsLimitTime>  
                  <StartTime>00:00:00</StartTime>  
                  <EndTime>23:59:59</EndTime>  
                  <IsLimitDate>0</IsLimitDate>  
                  <StartDay>2018/12/03</StartDay>  
                  <StartDayTime>00:00:00</StartDayTime>  
                  <EndDay>2019/12/03</EndDay>  
                  <EndDayTime>23:59:59</EndDayTime>  
                  <IsLimitWeek>0</IsLimitWeek>  
                  <LimitWeek>1,1,1,1,1,1,1</LimitWeek> 
                </Schedule>  
                <Trigger>
                  <Type>lightStrip</Type>  
                  <Value>0</Value> 
                </Trigger>  
                <FileSource>
                  <IsRelative>1</IsRelative>  
                  <FilePath>.\_Res_.files\F_8627B38BA221B6DFECFE4091F91A3D01_4575087.mp4</FilePath>  
                  <Resource_ID>293308</Resource_ID>  
                  <OriginName>H265_1080.mp4</OriginName> 
                </FileSource>  
                <ReserveAS>0</ReserveAS> 
              </Item> 
            </Items> 
          </Region> 
        </Regions> 
      </Page> 
    </Pages> 
  </Program> 
</Programs>

```