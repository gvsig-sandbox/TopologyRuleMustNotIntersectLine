# TopologyRuleMustNotIntersectLine

The rule requires that the lines not cross or overlap any part of another line in the same layer. But the endpoint of one line can touch the interior of another line. The errors report could be lines and points. Line errors are created if the lines are overlap, and points errors are created if lines intersect.

For example, it is useful when lines whose segments should never cross or occupy the same space with other lines. The lines intersection it is allowed only in the end point of the lines.
