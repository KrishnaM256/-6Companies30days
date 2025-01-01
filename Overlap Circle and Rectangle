class Solution {
    public boolean checkOverlap(int radius, int xCenter, int yCenter, int x1, int y1, int x2, int y2) {
        int x_nearest = Math.max(x1,Math.min(x2,xCenter));
        int y_nearest = Math.max(y1,Math.min(y2,yCenter));
        return Math.pow(xCenter-x_nearest,2)+Math.pow(yCenter-y_nearest,2)<=radius*radius;
    }
}
