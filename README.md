<div style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 14px; color: #333; line-height: 1.5;">
    
    <div style="background-color: #1e3c72; color: #ffffff; padding: 15px; text-align: center; border-radius: 6px 6px 0 0;">
        <h2 style="margin: 0; font-size: 20px;">🚩 SafeWalk Safety Report</h2>
    </div>

    <div style="border: 1px solid #e0e0e0; border-top: none; padding: 20px; border-radius: 0 0 6px 6px; background-color: #ffffff;">
        
        <p style="margin-top: 0;"><strong>Hello Admin,</strong></p>
        <p>A new safety hazard has been reported via the SafeWalk app.</p>

        <div style="margin: 20px 0; border-top: 1px dashed #cccccc;"></div>

        <table style="width: 100%; border-collapse: collapse;">
            
            <tr>
                <td style="padding: 8px 0; width: 40px; vertical-align: top;">
                    <div style="background-color: #e3f2fd; color: #1e3c72; width: 30px; height: 30px; border-radius: 50%; text-align: center; line-height: 30px; font-size: 16px;">
                        📍
                    </div>
                </td>
                <td style="padding: 8px 0; vertical-align: top;">
                    <div style="font-size: 12px; color: #888;">LOCATION</div>
                    <div style="font-size: 16px; font-weight: 600; color: #2c3e50;">
                        {{location}}
                    </div>
                </td>
            </tr>

            <tr>
                <td style="padding: 15px 0 8px 0; width: 40px; vertical-align: top;">
                    <div style="background-color: #ffeaea; color: #e74c3c; width: 30px; height: 30px; border-radius: 50%; text-align: center; line-height: 30px; font-size: 16px;">
                        📝
                    </div>
                </td>
                <td style="padding: 15px 0 8px 0; vertical-align: top;">
                    <div style="font-size: 12px; color: #888;">DESCRIPTION</div>
                    <div style="font-size: 15px; color: #333;">
                        {{description}}
                    </div>
                </td>
            </tr>

            <tr>
                <td style="padding: 15px 0 8px 0; width: 40px; vertical-align: top;">
                    <div style="background-color: #f0f0f0; color: #555; width: 30px; height: 30px; border-radius: 50%; text-align: center; line-height: 30px; font-size: 16px;">
                        📷
                    </div>
                </td>
                <td style="padding: 15px 0 8px 0; vertical-align: top;">
                    <div style="font-size: 12px; color: #888; margin-bottom: 5px;">ATTACHED PHOTO</div>
                    
                    <img src="{{attachment}}" alt="Report Image" style="max-width: 100%; width: 400px; border: 1px solid #ddd; border-radius: 4px; display: block;">
                    
                    <div style="font-size: 11px; color: #999; margin-top: 4px;">
                        (If no image was uploaded, this area may appear blank)
                    </div>
                </td>
            </tr>

        </table>

        <div style="margin: 20px 0; border-top: 1px dashed #cccccc;"></div>

        <div style="text-align: center; font-size: 12px; color: #999;">
            Submitted on {{time}} <br>
            SafeWalk Campus Safety App
        </div>

    </div>
</div>
